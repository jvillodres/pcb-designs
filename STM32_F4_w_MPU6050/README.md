# STM32 with IMU 📟

In this project you will find a compact PCB that integrates the **STM32F411CEU6** microcontroller with the gyroscope/accellerometer sensor **MPU6050** on a I2C bus. You can use it for robotic or movement data acquisition applications. 🤖

<p align="center">
  <img width="250" src="https://i.giphy.com/ZlRmaLNJgoRIA.webp">
</p>

## Preview 📸

Here is a little reference of what you'll find.

<p align="center">
  <img width="250" src="./Outputs/Layout/Top_3D_STM32F4_w_IMU.png">
  <img width="250" src="./Outputs/Layout/Bottom_3D_STM32F4_w_IMU.png">
</p>

## Technical Specs 📋

* **MCU:** STM32F411CEU6
* **Sensors:** MPU6050
* **Actuators:** None
* **Source:** 5V input via Micro-B USB 2.0
* **PCB Dimensions:** 36mm x 36mm x 1.67mm (4 layers)

## Project Structure 📚

The main editable files of the project you might want to look at.

| Type | Description |
| ---- | ----------- |
| [**Schematics**](Board_Schematic.SchDoc) | The **schematic sheet** file where you can find all the conections and components used |
| [**PCB**](Board_PCB.PcbDoc) | The **PCB file** where you can look at the layout, stackup, routing, and mechanical organization of the PCB. |
| [**Libraries**](../README.md#common-components-libraries--) | All the **external libraries** used for this project. If a symbol is not there, its because it was taken from the *Manufacturer Part Search* tool in **Altium**. |
| [**Datasheets**](./Datasheets/) | Some of the project's most relevant **datasheets**. The names correspond to their **MPNs**. |

## Project Outputs 🗂️

The previewable version of the project and the ready-to-go manufacturing files.

| Type | Description |
| ---- | ----------- |
| [**Schematics**](./Outputs/Schematics/STM32_F4_w_MPU6050.pdf) | All the **schematic sheets** of the project in **PDF** format, for the schematic editable file please refear to this [**section**](#project-structure-). |
| [**Layout**](./Outputs/Layout/Layout_STM32_F4_w_MPU6050.pdf) | The **layout** of the PCB in grayscale on **PDF** format, for the PCB editable file please refear to this [**section**](#project-structure-). |
| [**PCB render**](./Outputs/Layout/3D_STM32_F4_w_MPU6050.pdf) | A **3D-PDF render** of the PCB. *Please use a dedicated PDF viewer for opening the 3D-PDF file, it might not work well when previewing on **GitHub** or **Chrome**.* |
| [**Manufacturing files**](./Outputs/Manufacturing/) | Gerber, CPL and BOM files ready for manufacturing. The **BOM** file is filled with **JLCPCB** MPNs, also the **DRC** was based on JLCPCB capabilities. |

## Last but not least 🫂
©️ All the design credits go to [**Phil's Lab**](https://www.youtube.com/watch?v=PMEpQZ90f34), you can check out his [**YouTube channel**](https://www.youtube.com/@PhilsLab) to find more useful resources and projects.