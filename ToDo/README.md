# About

This github repo at https://github.com/agick/stm32tutorials, contains tutorials on features related to the STM32 microcontroller.

## Future Improvements
Instead of transmitting the measurement values one at a time we should try to set up the ADC - DMA and when the first half of the buffer is full it should be transmitted while the second half of the buffer fills up. When the second half of the buffer is being transmitted the first half of the buffer should be filled. Using the ADC - DMA would allow us to increase the sampling frequency and also ensure that we would have a constant sampling frequency. 

## App Improvements

We have decided to use the STM32 BLE Sensor App as a starting point as building an App that works perfectly with our device would take a lot more time and be out of the scope of this course. However, if we decided to build the proper App it could include digital signal processing that would allow us to filter the signal as well as extract features such as heart rate.






