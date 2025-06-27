# usbtmc_emulator_micropython
Emulated USBTMC device written in Micropython for STM32. This code can be easily modified to make a custom instrument.

stm32_blackpill_usbtmc_example.py is a Copilot (ChatGPT) auto-generated file which relies on the pyboard virtual com port. This has only been tested with [Pyvisa](https://pypi.org/project/PyVISA/) on Windows and Linux. stm32_blackpill_usbtmc_and_ap33772s.py is an example of a USBTMC interface for the AP33772S USB-PD 3.1 IC (using the I2C interface). 
