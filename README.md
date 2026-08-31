## Hi, I'm Francesca 👋

I am a Computer Engineering student at Concordia University and I enjoy working on hardware, embedded systems, and FPGA design with a focus toward space and aerospace applications.

### 🚀 What I'm Currently building
I am designing a **GSE (Ground Support Equipment) health monitoring board** for Space Concordia's Liquid Rocketry Division (Project ASTR, which is short for Astraeus, the Greek Titan god of dusk, stars, and planets!). The board handles two jobs:
- **CAN FD ↔ Ethernet bridge** — bridges the rocket's internal CAN FD network to GSE computers over Ethernet
- **Panel/board health monitoring** — power supply health, ambient temp/humidity inside a sealed IP66 enclosure, breaker trip status, valve energization status, and E-stop/safety relay status

**Core architecture:**
- MCU: STM32H723VE
- Ethernet: LAN8720A PHY over RMII (internal MAC + lwIP)
- CAN transceiver: ATA6563
- Power: 120VAC input (generator-fed, isolated from panel supplies by design) via Mean Well MPM-05-3.3, custom Altium symbol/footprint built from scratch

### 🛠️ Skills & tools
`VHDL` `C/C++` `Altium Designer` `LTspice` `STM32` `CAN/CAN FD` `Ethernet/RMII` `Git`
