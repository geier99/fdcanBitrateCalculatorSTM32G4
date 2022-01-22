# fdcanBitrateCalculatorSTM32G4
Auxiliary tool for the fdcan baud rate calculation for STM32

## Hints
- This calculation tool is for the STM32-HAL (FDCAN HAL module driver), the result value have to be set through the HAL_FDCAN_Init() function, and this is the reason why in my excel tool I am starting from 1 and not from 0 for the parameter values.
- Please check the Wiki [Wiki](https://github.com/geier99/fdcanBitrateCalculatorSTM32G4/wiki).
- A short description how to use it, is inside the Excel-Sheet
