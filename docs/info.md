<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

This circuit is a 4X4 memory adress decoder. Two input bits select one of four wordlines (rows), and the other two bits select one of four bitlines (columns). This allows the circuit to select one of 16 possible memory locations.

## How to test

Apply 16 input combinations (0000 to 1111) and verify that only one wordline and one bitline are active for each adress.

## External hardware

4 push buttons or switches or the input bits.
8 LEDs to monutor the wordline and bitline outputs.
Current-limiting resistors for the LEDs.
DC power supply.
