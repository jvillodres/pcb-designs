# ESP32 + PCB Antenna (No RF shield) 🛜

In this project, you will find a development board based on the **ESP32-C3** SoC. This version lacks an RF shield and features an integrated onboard antenna. 📡

<p align="center">
  <img width="250" src="https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExcXEzNng4MjVzMTU3M285MGUyZzJ6bm0xNnluNzk4MnBldXZoZGp5aSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/YSGVoeI1TPZ9s8RNCg/giphy.gif">
</p>

## Preview 📸

Here is a brief overview of what you will find.

<p align="center">
  <!-- <img width="250" src="./Outputs/Layout/Top_3D_STM32F4_w_IMU.png">
  <img width="250" src="./Outputs/Layout/Bottom_3D_STM32F4_w_IMU.png"> -->
</p>

## Technical Specs 📋

* **MCU:** ESP32-C3
* **Sensors:** None
* **Actuators:** None
* **Source:** 5V input via Type-C USB 2.0
* **PCB Dimensions:** height x width x thickness (n layers)

## Project Structure 📚

The main editable project files you might want to review:

| Type | Description |
| ---- | ----------- |
| [**Schematics**](.) | The **schematic sheets** files, where all conections and components used can be found. |
| [**PCB**](ESP32_PCB.PcbDoc) | The **PCB file** where the layout, layer stackup, routing, and mechanical organization of the PCB can be view. |
| [**Libraries**](../README.md#common-components-libraries--) | All **external libraries** used in this project. If a symbol does not appear, it is because it was obtained using **Altium's** *Manufacturer Part Search* tool. |
| [**Datasheets**](./Datasheets/) | Some of the most relevant **datasheets** for the project. The names correspond to their **MPNs**. |

## Project Outputs 🗂️

The project version for preview and the ready-to-go manufacturing files.

| Type | Description |
| ---- | ----------- |
| [**Schematics**](./Outputs/Schematics/ESP32-Antenna-NoPackage.pdf) | All project **schematic sheets** in **PDF** format, for the editable schematic file, please refear to this [**section**](#project-structure-). |
| [**Layout**](./Outputs/Layout/layout_file.pdf) | The **PCB design** in grayscale and **PDF** format, for the editable PCB file please refear to this [**section**](#project-structure-). |
| [**PCB render**](./Outputs/Layout/3D_file.pdf) | A **3D-PDF render** of the PCB. *Please use a dedicated PDF viewer to open the 3D-PDF file, it may not work correctly when previewed in **GitHub** or **Chrome**.* |
| [**Manufacturing files**](./Outputs/Manufacturing/) | Gerber, CPL and BOM files ready for manufacturing. The **BOM** file includes **JLCPCB** MPNs, also the **DRC** was based on JLCPCB capabilities. |

## Last but not least 🫂
©️ Full credit for the design goes to [**Phil's Lab**](https://www.youtube.com/watch?v=yxU_Kw2de08), you can check out his [**YouTube channel**](https://www.youtube.com/@PhilsLab) to find more useful resources and projects.