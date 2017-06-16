# Pulse Oximeter
This is microcontroller software of our pulse oximeter device being developed for _Advanced Programming Course_ in 2017 fall semester. The microcontroller used is a STM32F407VG. The software is developed using STM32 **HAL** library and STM32 **Cube**.
# What this code does?
1. Two phase shifted PWMs are generated as below:

<p align="center">
	<img src="https://image.ibb.co/hviDxk/pwm.jpg">
</p>

2. ADC is triggered by a 200Hz timer in DMA mode and generates 2000 samples of each two channels.
3. Samples are sent over UART to PC for further analysis.

# Contributers
* [Mohammad Hossein Tavakoli Bina](https://github.com/mhtb32)
* [Mohammad Ebrahimi](https://github.com/Ebik95) :bear:
* [Hamidreza Ehsani Chimeh](https://github.com/hrehsani) :dog2:
