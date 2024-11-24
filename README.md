# CLion dev workflow test

- works perfect:11/24/2024 
  - LED
  - USART
  - SH1106
- just for testing 
  - sometimes I always forget to commit🤣🤣 
- configs for initialization
  - gpios
  ![gpios](images_for_stm32cubemx_init/gpios.png)
  - usart
  ![usart_init](images_for_stm32cubemx_init/usart_init.png)
  - usart
  ![spi_init](images_for_stm32cubemx_init/spi_init.png)
  - overall
  ![pinout_overall_view](images_for_stm32cubemx_init/pinout_overall_view.png)
# chips and peripherals 
- stm32f407vet6
- cmsis-dap
- sh1106 0.96'' OLED
- onboard led linked to pc0

# where is the driver for sh1106
- [this is the link](https://github.com/afiskon/stm32-ssd1306)
> Maybe you will find the driver for sh1106 in my project is not the completely same 
as the one I provided in the link above, that is because I only modified the function name such as `SSD1306_Init()` to
`SH1106_Init()`, and that is all I modified. Hope this will not annoy you.

# toolchain
- [arm-gnu](https://developer.arm.com/-/media/Files/downloads/gnu/13.3.rel1/binrel/arm-gnu-toolchain-13.3.rel1-mingw-w64-i686-arm-none-eabi.zip)
- [msys2](https://www.msys2.org/)
  - mingw64
  - openocd