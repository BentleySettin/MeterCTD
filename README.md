# 🚀 Welcome to this Github Project!

## 🌟 Highlights

- Measuring conductivity, temperature, and depth (CTD)
- Low-cost sensor 
- Open Source data
- Cellular cabailities
- Easy integration for research and educational purposes!


## ℹ️ Overview

This repository outlines the integration of a Meter CTD and a Particle Boron. These two sensors combined will allow for accurate data collection of conductivity, water temperature, depth, and air pressure with easy cellular communication for real-time data and visualization. 

Explore and learn more about these two electronics we are using here: 
- [Meter CTD](https://metergroup.com/products/hydros-21/)
  ![image](https://github.com/user-attachments/assets/98af398b-e5e4-493e-81ec-0d542da2fe86)

- [Particle Boron 404x](https://store.particle.io/products/boron-lte-cat-m1-noram-with-ethersim-4th-gen?srsltid=AfmBOorHx31GWq4IeQavaX2ePNGsbMFQteTf-O0mL9GnkE8jHbQbHShg)
  ![image](https://github.com/user-attachments/assets/596abf2d-71be-488b-9b11-406e2439d4bf)


## ⬇️ How to get around!

What are you looking for in this repository?
- Updated scripts with current libraries? Go to [Firmware](https://github.com/BentleySettin/MeterCTD/tree/ba0404429f45d6b78e378566db7e1a76302030d5/Firmware)!
- How to electronically connect the MeterCTD and Boron using wires? Go to the [Circuit Diagram](https://github.com/BentleySettin/MeterCTD/blob/ba0404429f45d6b78e378566db7e1a76302030d5/Fabrication/CircuitDiagram.png)!

## 💭 Learn more about DDI Interface

The interface we chose to communicate between the Particle Boron and Meter CTD is the DDI Interface. The HYDROS Meter CTD can function using DDI interface or SDI-12 interface. SDI-12 interface is a standardized communication protocol used to connect sensors with data loggers and data acquisition systems. It allows multiple uniquely addressed sensors to operate on a shared 3-wire bus consisting of power, ground, and data lines. Due to this project focusing on one addressed sensor we chose the DDI interface. The DDI serial protocol is used by METER data loggers to collect data from the sensor. It operates over a reciever only data line, meaning data is transmitted only from the sensor to the receiver. Typically, the receiving end is either a microprocessor UART or a general-purpose I/O pin configured to receive data using a bit-banging method. 

Information was supplied from this [HYDROS 21 Integrator Guide](https://library.metergroup.com/Integrator%20Guide/18281_HYDROS21(CTD)_GEN1.pdf?_gl=1*1cipulk*_gcl_au*MTIwMzA0NDExMC4xNzM3NDk3MDQ1).

### ✍️ Authors

Hello, I am [Bentley Settin](https://github.com/BentleySettin)! I am a M.S. Student at UNCW working under[ Dr. Phil Bresnahan](https://github.com/SUPScientist). Check out our [lab](https://github.com/COAST-Lab) and all the fun projects we have going on!  

