# LED Blink

## 🧩 Hardware
- Board: NUCLEO-F302R8
- LED / Button / Pins: PA5
- Timer / UART / PWM: TIM2

## ⚙️ Description
This project provides led blink in 0.5 seconds.  
Example: Uses TIM2 timer to make the LED blink at 0.5-second intervals.

## 🧠 Important Notes
- Prescaler = [e.g., 7200 - 1]
- Period = [e.g., 5000 - 1]
- Interrupt active: HAL_TIM_Base_Start_IT(&htim2)
- CubeIDE version: [e.g., 1.19.0]
- CubeMX `.ioc` file is included for project configuration.

## 🔧 Usage
1. Open STM32CubeIDE.
2. Open the `.ioc` file and verify the pins and clock settings for your board.
3. Build the project and flash it to the board.
4. Adjust pin assignments and timer values if necessary for your board.

## ⚡ Note
This project **may not work directly on every STM32 board**.  
- Users should check their board's pin and clock configuration.  
- Timer and UART settings may vary across different boards.

![LED](https://github.com/user-attachments/assets/710c9fa5-2b72-4605-88e1-c693dc9e1a2a)

