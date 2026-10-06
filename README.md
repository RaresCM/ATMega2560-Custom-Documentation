# ATMega2560-Custom-Documentation
This is a custom made memory registry lookup table I made for the ATMega2560 AVR chip.

<img width="1022" height="740" alt="image" src="https://github.com/user-attachments/assets/0c17c0b9-ecfd-4b29-98e1-d1ffa3c312d7" />
<img width="1022" height="680" alt="image" src="https://github.com/user-attachments/assets/a434dc3d-6ffe-418c-b6c1-6b006446e950" />

It contains the memory mapping of most addressable memory registers on the chip to be able to initialize or set up the chip for your projects. As seen in the pictures its a simple straight to the point look up table/reference to help code directly in bare metal C. Everything is referenced directly from the attached official ATmega2560 documentation. Cells denoted in green are registers that are automatically hadneled at the hardware level or very rarely toucehd by code directly. It does omit some memory registers found in the offical datasheet as those are direclty handleed by hadrware and are recommended to not be direclty hadneled by code.
