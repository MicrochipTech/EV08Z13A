# **Microchip Timberwolf™ Development Kit**   

Microchip’s EV08Z13A evaluation board features Microchip’s Timberwolf audio processor, capable of running the full family of Timberwolf technology firmware. The EV08Z13A is designed to help developers quickly prototype and demonstrate high-quality audio processing algorithms such as full-duplex stereo echo cancellation, beamforming, noise reduction, dynamic range control etc.

The EV08Z13A evaluation board can be used to easily demonstrate algorithms for 2-way voice communication and embedded speech recognition applications by using the Timberwolf Demo Tool software. Once ready for application-specific customization, the EV08Z13A can be configured and tuned with the Microchip MiTuner GUI software.


## EV08Z13A Development Kit Features
-	Timberwolf Audio DSP 
-	Four on-board digital MEMS Microphones in recommended array geometries.
-	Headphone/Speaker Output Jack
-	I2S Port A Header
-	USB Receptacle
-	Power
-	Audio via USB to I2S Port B bridge
-	UART Debug Headers for interfacing with MiTuner and Demo Tool
-	Raspberry Pi 3B 40-pin Header
-	On-Board Flash Memory
-	I2C LED Controller with 12 RGB LEDs

Kit also includes:
-	miniUSB Cable for Power & Audio
-	USB-to-TTL Serial (FTDI) Cable for UART

## EV08Z13A Development Kit Benefits
-	Demonstrate full family of Timberwolf Products (along with Timberwolf Demo Tool Software)
-	Evaluate, prototype, debug and tune with single platform. (along with MiTuner GUI Software)
-	Supports all recommended microphone array geometries with on-board MEMS microphones.
-	USB – I2S bridge is configured to be a plug-and-play bi-directional audio interface between Timberwolf DSP and PC. 
-	Additional mic, DAC, and GPIO options with JMMA1 Header

# Ready to Get Started?

## Step 1: Order Board 
[Order the EV08Z13A development board](https://www.microchip.com/DevelopmentTools/ProductDetails/PartNO/EV08Z13A). Once you have purchased your board, follow the remainder of these steps to get started with evaluating the Microchip Timberwolf Audio Processor.  

## Step 2: Software Setup
-	Download the Timberwolf Demo Tool Package on to a Windows PC, and unzip to a known location.
-	Install the included FTDI Driver by running CDM21228_Setup.exe.
-	Install Timberwolf Demo Tool Setup.exe 
-	For Windows 7/8 users, install the included Timberwolf Virtual COM Port driver by right-clicking twusbcom.inf and clicking Install.
-	Restart your PC. 

## Step 3: Hardware Setup
-	Connect the EV08Z13A Development Board to your Windows PC using the included mini USB cable. Ensure that red POWER LED is solid ON indicating USB power. This mini USB connection also enables USB Audio connectivity between the Board and the PC. 
-	Connect the JAIB1 header to the PC using the included USB-to-TTL cable as shown in the following picture. 

![image](https://user-images.githubusercontent.com/26750703/86989971-339ae880-c161-11ea-9c91-9a89fdc5a100.png)
 
The EV08Z13A has a standard 3.5mm audio jack for headphone or speaker output. Any pair of headphones and speakers will be required to evaluate many of the Timberwolf Demos. The audio output device should have minimal processing for the demos to run properly. 

## Step 4: Run Timberwolf Demos 
Start the Timberwolf Demo Tool. Choose the part number and demo to load firmware image, and speaker output setup. 

![image](https://user-images.githubusercontent.com/26750703/86989991-3d245080-c161-11ea-96a8-78c4ea549681.png)

![image](https://user-images.githubusercontent.com/26750703/86990003-41e90480-c161-11ea-8ab7-15acfc8900fe.png)

---
For Quick Troubleshooting & Support, submit a case [here](https://microchipsupport.force.com/s/article/How-to-submit-a-case). 
