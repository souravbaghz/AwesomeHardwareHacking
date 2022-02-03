<p align="center">
  <img  width="1200" src="banner.png" />
</p>

***
<h2>Common Attack Methodology:</h2>

<b>Step | Description</b>
---- | ----
1.Intel Gathering<br />(Recon) | Open the target device carefully without damaging anything inside it and begin gathering information such as the embedded device's operating system, supported external peripherals, chip-sets used, types of storage and memory used, and other relevant information that could be useful in future attacks. You may also need datasheets and documentation which you can try to find from public resources.
2.Device Analysis<br />(Exterior) | Visual inspection, both external and internal, should be used to identify as much information as possible from the attacker's perspective. Try to figure out what you're looking at from the outside. What are the different interface choices, such as USB ports, SD-Card card slots, or an Ethernet port, that are powered by batteries or an adapter? Are there any labels on the device, and if so, what information do they contain.
2.Device Analysis<br />(Interior) | After you've completed the external check, open up the device and examine the printed circuit board (PCB). Identifying all of the different chipsets that are present, reading the datasheet to understand what each component does, and taking notes on the various information that we find on the datasheet.
3.Identify Communication Interfaces | Look into all of the device's various interface options. It may be simple and right in front of your eyes if you have already acquired knowledge, or it may be difficult to find those interfaces.
4.Acquire Information | We can use a collection of tools to connect with the target device across the supplied interface to read/write data to the chip once we've discovered the available communication interface.
5.Exploiting Software | Following the previous stage of gaining access to the target device via a specific hardware interface, we can use numerous software exploitation techniques such as dumping firmware, writing new content to a specific memory, manipulating ongoing processes, and so on.

***

<h2>Most Common Interfaces Found in Hardware:</h2>

<b>Topic/Concept | Description/Resource</b>
---- | ----
UART | One of the most often used communication protocols in embedded systems is UART.<br /> UART turns the parallel data it receives into a serial bit stream of data that is potentially easier to interact with.<br /> It is used for shell access and a favorite interface of any hardware hacker.<br />[Abusing UART](https://www.ethicalhacker.net/columns/sindermann/hardware-hacking-101-lesson-3-abusing-uart-u-are-root/)
JTAG | From the perspective of a hacker, JTAG serves a variety of functions, including the ability to read/write data, debug running processes, and change the code execution flow.<br />[JTAG Explained](https://blog.senr.io/blog/jtag-explained)
SPI & I2C | SPI & I2C both are a serial communication protocol that is commonly used in Flash and EEPROM. We can dump data from it because it includes storage, which might include firmware, hardcoded keys, and other sensitive information, depending on type of target we have.<br />[Dumping Your First Firmware](https://blog.nvisium.com/intro-to-hardware-hacking-dumping-your-first-firmware)

***
### 🤝 Connect with me
[![Instagram: souravbaghz](https://img.shields.io/badge/instagram-%23E4405F.svg?&style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/souravbaghz)
[![GitHub souravbaghz](https://img.shields.io/badge/github-%23000000.svg?&style=for-the-badge&logo=github)](https://github.com/souravbaghz)
[![Twitter souravbaghz](https://img.shields.io/badge/twitter-%231DA1F2.svg?&style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/souravbaghz)
