# PCB-Design

### Files:
- overview.png : A visual overview of the project and results
- pcbDesign.kicad_pcb : PCB layout file in KiCAD
- signalGeneratorGerber.zip : Gerber files

### Description:

A signal generator PCB design project performed as part of a 40 hour course through the UBC PHAS Elab, Fall 2022.  A 15V DC signal is passed through a voltage regulator to produce 5V DC.  The 5V is passed through a 5V -> -5V converter to power the rails of an op-amp that can control output signal amplitude.  5V powers a 100kHz Timer/Oscillator that produces a squarewave signal that can be tuned in combination with the potentiometers and the op-amp.  Tuned signal can be read from a through-hole test port.

![alt text](https://github.com/chipnbits/PCB-Design/blob/main/overview.png)

Project phases included:

#### Design
- Creating a schematic in EDA software (KiCad), including additions to the parts library.
- Creating custom component footprints to match manufacturer specifications.
- Review of good design priciples for PCB circuit layout.
- Manual layout of circuit onto a two-layer PCB, design rules specifications, variable width traces.
- Custom silk screen layering, sizing, and drill holes for ease of assembly.
- Gerber file production and PCB ordering.

#### Assembly
- Manual soldering of surface mount components with a Sainsmart TS-100 Iron.
- Testing and validation with digital oscilloscope and multimeter.
- Use of one jumper wire to correct a connection issue not flagged properly by EDA.





