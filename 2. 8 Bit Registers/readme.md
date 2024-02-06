## 2: Registers

The 8-bit register design includes 3 input control signals:
- **!Load:** Active-low signal that controls data entry to the register
- **Clock:** The register flip flops are positive-edge-triggered
- **Enable:** Active-high signal that controls the data output

I have developed and tested different designs of 8-bit registers using the following 74xx series IC Flip Flop chips:
- [**74 173:**](https://www.ti.com/lit/ds/symlink/sn54ls173a.pdf?ts=1707165415452&ref_url=https%253A%252F%252Fwww.google.com%252F) 4-Bit D-Type Registers With 3-State Outputs
- [**74 273:**](https://www.ti.com/lit/ds/symlink/sn54ls273-sp.pdf?ts=1707170341653) Octal D-Type Flip-Flop With Clear
- [**74 374:**](https://www.ti.com/lit/ds/symlink/sn74hct374.pdf?ts=1707188260498&ref_url=https%253A%252F%252Fwww.google.com%252F) Octal Edge-Triggered D-Type Flip-Flops With 3-State Outputs
- [**74 377:**](https://www.ti.com/lit/ds/symlink/sn74hct377.pdf?ts=1707184047138&ref_url=https%253A%252F%252Fwww.google.com%252F) Octal D-Type Flip-Flops With Clock Enable
- [**74 574:**](https://www.ti.com/lit/ds/symlink/sn74hc574.pdf?ts=1707141952589&ref_url=https%253A%252F%252Fwww.google.com%252F) Octal Edge-Triggered D-Type Flip-Flops With 3-State Outputs (Alternative pin layout of the 74 374)


