# STM32F407_SPI_DAC104S085
Repo for test the Texas Instrument SPI DAC "DAC104S085" with STM32F407VG
## The code have the DAC function: Write_DAC104S085 (uint8_t channel, uint8_t mode, unsigned short value)
### uint8_t channel: is the DAC channel number. The channels are divided as following
>0: Channel A  
>1: Channel B  
>2: Channel C  
>3: Channel D  
  
### uint8_t mode: is the DAC mode of operation. The mode of operation is divided as following
>0: Write to specified register but do not update outputs.  
>1: Write to specified register and update outputs.  
>2: Write to all registers and update outputs.  
>3: Power-down outputs.  
### unsigned short value: is the 10-bit voltage value of the DAC channel, it can be between 0 to 1023
