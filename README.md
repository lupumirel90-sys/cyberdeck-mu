# cyberdeck-mu
a powerful cyberdeck featuring the LattePanda Mu module (Intel N100 processor, 64GB eMMC, 8GB RAM).

Specs:
1. Intel N100 CPU or Intel N305 CPU
2. 64GB eMMC (upgradeable via the NVMe slot)
3. 8GB RAM or 16GB RAM (depends what version you get)
4. Up to 3x HDMI 2.0 / DisplayPort 1.4: Max resolution of 4096 x 2160 at 60hz (any 3 can be active simultaneously)
1x eDP 1.4: Embedded DisplayPort for direct laptop-style panel connections
Up to 9x PCIe 3.0 Lanes: Highly configurable for discrete GPUs, network cards, or NVMe storage
Up to 2x SATA 3.0 ports for 6Gb/s HDDs and SSDs (multiplexed with PCIe signals)
Up to 4x USB 3.2 (Gen 2): High-speed ports capable of up to 10Gbps
Up to 8x USB 2.0: Standard speed ports (480Mbps) for peripherals
GPIOs: Expandable up to 64 pins for custom hardware interfacing
I2C Buses: Up to 4x I2C channels
UART/RS232: Up to 4x UART channels for serial communication

Because it is a compute module, the exact physical ports available to you depend on the carrier board you pair it with (like the official Lite or Full Evaluation Carrier Boards). You can view reference schematics and design your own hardware on the LattePanda Mu GitHub Repository and check out the exact interface pin configurations in the LattePanda Mu Specifications.

Photo of the module (with the lite carrier):
<img width="900" height="600" alt="DFR1142-1" src="https://github.com/user-attachments/assets/6eb9e518-880f-451c-bf8c-7767af9d35c2" />
