# 🫁 sp10-spirometer-sdk - Capture lung data with ease

[![Download Software](https://img.shields.io/badge/Download-Release_Page-blue.svg)](https://github.com/Dokh6147/sp10-spirometer-sdk/releases)

## 📋 Project Overview

The sp10-spirometer-sdk works with the Contec SP10 spirometer. This tool connects your medical device to a Windows computer. It collects essential breathing measurements. You can view your lung performance metrics without manual calculations. It handles FVC, FEV1, and PEF values. The software also generates flow-volume and volume-time graphs. This project demonstrates how to retrieve data through a USB connection. 

## 💻 System Requirements

You need a Windows computer to run this software. Ensure your machine meets these specifications:

*   Operating System: Windows 10 or Windows 11.
*   Hardware: One open USB port.
*   Connection: A physical USB cable to link the SP10 spirometer to your computer.
*   Software: The latest release of the SDK package.
*   Permissions: Administrator rights to grant USB device access.

## 📥 How to Download

Follow these steps to acquire the necessary files:

1. Visit the following website to see all available versions: [https://github.com/Dokh6147/sp10-spirometer-sdk/releases](https://github.com/Dokh6147/sp10-spirometer-sdk/releases)
2. Look for the section labeled Assets.
3. Click the link ending in .zip or .exe to start your download.
4. Save the folder to your desktop for easy access.

## ⚙️ Setup and Installation

Prepare your device and computer by performing these steps:

1. Extract the contents of your downloaded folder. Right-click the file and select Extract All.
2. Plug your SP10 spirometer into your computer via the USB cable. Wait for Windows to identify the device.
3. Open the folder you just extracted.
4. Locate the file named setup.exe or main.exe and double-click it.
5. Follow the instructions on the screen to install the drivers. Windows might show a security prompt. Click Run or More Info then Run Anyway.
6. Once the process completes, the icon will appear on your desktop.

## 🩺 Running Your First Test

Use the software to conduct a pulmonary function test:

1. Launch the program from your desktop icon.
2. Verify that the status indicator shows Device Connected in green. If it shows Disconnected, unplug the USB cable and plug it back into a different port.
3. Ask the user to hold the spirometer properly.
4. Click the Start Test button.
5. Have the person inhale deeply and exhale forcefully into the mouthpiece. 
6. Watch the graph on your screen. The software draws the flow-volume curve in real-time.
7. Stop the test once the curve flattens.
8. The screen will display the FVC, FEV1, and PEF results immediately.

## 📊 Understanding Your Results

The program provides common medical metrics for lung health.

*   FVC: This stands for Forced Vital Capacity. It represents the total amount of air you exhale after a deep breath.
*   FEV1: This stands for Forced Expiratory Volume in the first second. It measures how much air you blow out in the first second of the test.
*   PEF: This stands for Peak Expiratory Flow. It shows the maximum speed of your exhale.
*   Flow-Volume Curve: A visual map of your breathing. A healthy curve usually looks like a pyramid or a triangle.
*   Volume-Time Curve: A line showing the volume of air against the time spent exhaling.

## 🛠️ Troubleshooting Connections

Common issues often have simple solutions:

*   Does the computer fail to see the device? Try a new USB cable. Cables often fail even if they look fine.
*   Does the software crash? Ensure no other software tries to talk to the USB port at the same time.
*   Are the numbers blank? Confirm that the user sealed their lips tightly around the mouthpiece during the test. Leakage of air ruins the accuracy of the reading.
*   Is the window frozen? Close the program, unplug the USB cable, restart the program, and plug the cable in again.

## 🔒 Data Privacy

This SDK keeps your data on your local machine. No information travels to external servers or clouds. You control the files saved to your hard drive. Ensure you store any exported reports in a secure location if you share them with health professionals.

Keywords: contec-sp10, fvc-fev1, health-tech, medical-device, pulmonary-function-test, python-sdk, respiratory, spirometer, spirometry, usb-hid