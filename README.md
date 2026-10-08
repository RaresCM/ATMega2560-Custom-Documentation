# ATmega 2560 Custom Memory Register Map
## A custom memory register map/look-up table for the ATmega 2560 AVR chip.


<img width="2072" height="308" alt="image" src="https://github.com/user-attachments/assets/fd2d7a05-042f-4811-b335-edfc8b662e06" />
<img width="2072" height="385" alt="image" src="https://github.com/user-attachments/assets/bc5aecda-2827-4ace-9223-82a61a8201c8" />


## Overview
Memory mapping of most addressable memory registers on the chip to be able to initialize or set up the chip. 


As seen in the example pictures, a straight to the point look-up table/reference to help code in bare metal C. Everything is referenced from the attached official ATmega 2560 documentation. 


Cells coloured green are registers that are automatically handled at the hardware level or very rarely touched by code directly. It omits some memory registers found in the official datasheet as those are directly handled by hardware and are recommended to not be directly handled by code. 


The PDF is a download of a Google Sheet so it should be easy to download and modify the file or translate it back to Sheets or to Excel.
