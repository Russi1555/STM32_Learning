# STM32 Learning

This repository contains my personal STM32 learning projects and experiments. It was primarily created for my own reference and study purposes, but if it helps someone else get started with STM32 development, even better!

## Installing the Required Tools

Before getting started, install all the required tools by following ST's official guide:

https://wiki.st.com/stm32mcu/wiki/STM32StepByStep:Step1_Tools_installation#cite_note-4

It is recommended to install:

* STM32CubeIDE
* STM32CubeMX
* ST-LINK drivers (if they are not installed automatically)
* The STM32 firmware packages required for the microcontroller families you intend to use

---

## Creating a New Project

1. Open **STM32CubeMX**.
2. Click **New Project**.
3. Select the appropriate **development board** or **microcontroller**.
4. Configure the pins, peripherals, and other settings in the **Pinout & Configuration** tab.
5. Open the **Project Manager** tab and configure:

   * Project Name
   * Project Location
   * **Toolchain / IDE:** `STM32CubeIDE`
6. Click **Generate Code**.
7. Open the generated project in **STM32CubeIDE**.
8. Create a **Debug/Run** configuration to build, flash, and debug the application on your board.

---

## Opening an Existing Project

1. Open **STM32CubeIDE**.

2. Select:

   ```
   File → Import...
   ```

3. Choose:

   ```
   General → Existing Projects into Workspace
   ```

4. Select the project's folder.

5. Click **Finish**.

The project is now ready to be built, flashed, and debugged using ST-LINK.
