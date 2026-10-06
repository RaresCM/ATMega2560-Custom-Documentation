# ATMega2560-Custom-Documentation
This is a custom made memory registry lookup table I made for the ATMega2560 AVR chip.
<img width="1022" height="740" alt="image" src="https://github.com/user-attachments/assets/0c17c0b9-ecfd-4b29-98e1-d1ffa3c312d7" />
<img width="1022" height="680" alt="image" src="https://github.com/user-attachments/assets/a434dc3d-6ffe-418c-b6c1-6b006446e950" />
It contains the memory mapping of most addressable memory registers on the chip to be able to initialize or set up the chip for your projects. As seen in the example pictures of some register mappings its a simple straight to the point look up table/reference to help code directly in bare metal C. Everything is referenced directly from the attached official ATmega2560 documentation. Cells denoted in green are registers that are automatically handled at the hardware level or very rarely touched by code directly. It does omit some memory registers found in the official datasheet as those are directly handled by hardware and are recommended to not be directly handled by code. 

The PDF is in a large format and can easily be adjusted, edited or cut according to your needs using a PDF editor or can be converted back into Excel/Google Sheets.
