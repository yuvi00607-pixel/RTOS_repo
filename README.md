# STM32F446RE Embedded Systems & FreeRTOS Experiments

This repository contains hands-on embedded systems and FreeRTOS experiments performed on the STM32F446RE microcontroller using STM32CubeIDE and Embedded C.

The experiments focus on peripheral interfacing, real-time task scheduling, inter-task communication, synchronization techniques, and embedded firmware development.

---

## Hardware & Software Used

### Hardware
- STM32F446RE Nucleo Board
- HC-SR04 Ultrasonic Sensor
- LEDs
- Push Buttons
- USB-UART Interface

### Software
- STM32CubeIDE
- FreeRTOS
- Embedded C
- STM32CubeMX

---

## Features

- GPIO Programming
- LED Blinking
- Push Button Interfacing
- PWM Signal Generation
- Ultrasonic Sensor Interfacing
- Super Loop Programming
- FreeRTOS Task Scheduling
- Task Priorities
- Binary and Counting Semaphores
- Queue Communication
- UART Communication
- External Interrupt Handling

---

## List of Experiments

| No. | Experiment |
|----|-------------|
| 1 | GPIO LED Blinking using software delay |
| 2 | Push Button Interfacing with LED Toggle |
| 3 | HC-SR04 Ultrasonic Sensor Interfacing |
| 4 | PWM LED Brightness Control |
| 5 | Super Loop-Based Embedded Programming |
| 6 | FreeRTOS Single Task LED Blinking |
| 7 | FreeRTOS Multi-Tasking with Priorities |
| 8 | EXTI Interrupt with Semaphore Synchronization |
| 9 | Queue-Based UART Communication |
| 10 | Counting Semaphore Resource Sharing |

---

## Repository Structure

```text
STM32-FreeRTOS-Experiments/
│
 1_GPIO_Output_LED_Blink/
 2_GPIO_Button_Input/
 3_HCSR04_Ultrasonic_Sensor/
 4_PWM_LED_Control/
 5_Super_Loop_Programming/
 6_FreeRTOS_Single_Task/
 7_FreeRTOS_Task_Priority/
 8_EXTI_Semaphore/
 9_Queue_UART_Communication/
 10_Counting_Semaphore/
 Images/
 Docs/
 README.md
 .gitignore
```

---

## FreeRTOS Concepts Covered

### Task Management
- Task Creation
- Task Scheduling
- Task Priority

### Inter-Task Communication
- Queues
- Task Notifications

### Synchronization
- Binary Semaphore
- Counting Semaphore
- Mutex Concepts

### Interrupt Handling
- EXTI Interrupts
- ISR Synchronization

---

## Project Demonstrations

Add screenshots, circuit diagrams, serial monitor outputs, and demo images inside the `Images/` folder.

Example:

```md
![Demo](Images/demo.png)
```

---

## How to Run the Projects

1. Open STM32CubeIDE
2. Import the desired project folder
3. Build the project
4. Flash the code to STM32F446RE board
5. Observe output using LEDs, Serial Monitor, or connected peripherals

---

## Tools & Technologies

- Embedded C
- STM32CubeIDE
- FreeRTOS
- ARM Cortex-M4
- UART
- GPIO
- PWM
- EXTI
- Timers

---

## Learning Objectives

This repository was created to:
- Understand embedded systems programming
- Learn FreeRTOS fundamentals
- Develop real-time applications
- Practice STM32 peripheral interfacing
- Build embedded firmware development skills

---

## Future Improvements

- SPI Communication
- I2C Communication
- DMA with FreeRTOS
- RTOS-Based Sensor Fusion
- Real-Time Data Logging
- OLED/LCD Interfacing

---

## License

This project is licensed under the MIT License.
