
The Nexus-Drive FD is an intelligent FOC (Field Oriented Control) servo controller designed to drive X and Y axes with industrial-grade dynamics. It offloads real-time motor physics from the Master H7, communicating via high-speed CAN FD.
Key Hardware Features:
- MCU: STM32G431 (170MHz, Cordic math accelerator for FOC).
- Power Stage: 3-Phase Gate Driver (DRV8301 or DRV8323) with 6x High-current N-CH MOSFETs (PowerFLAT 5x6).
- Current Sensing: Dual or Triple shunt resistors with G431 internal OPAMPs for precise torque control.
- Feedback: AS5047P / AS5048 Magnetic Absolute Encoder (14-bit SPI) for closed-loop position control.
- Safety: Hardware Overcurrent, Overtemperature, and Stall Detection reporting back to Nexus-H7 via CAN FD.
- Performance: Silent operation (Stealth), Zero step loss, and "Soft Collision" detection through real-time torque monitoring.
