# KeyDrop - Automatic Keyboard Commands with ATTINY85

## Overview

The [ATTINY85](https://www.aliexpress.com/item/2040316211.html?spm=a2g0o.productlist.main.1.1db340abP84R7c&algo_pvid=1ef154b1-9ee1-4fd6-8b81-a7673a4bcb84&algo_exp_id=1ef154b1-9ee1-4fd6-8b81-a7673a4bcb84-0&pdp_ext_f=%7B%22order%22%3A%221416%22%2C%22eval%22%3A%221%22%7D&pdp_npi=6%40dis%21CAD%213.60%213.60%21%21%212.55%212.55%21%402103247017569311319098223e73a0%2158307777832%21sea%21CA%21228479340%21X%211%210%21n_tag%3A-29919%3Bd%3A9a4ae1e%3Bm03_new_user%3A-29895&curPageLogUid=lrwXY8rw3ZEE&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A2040316211%7C_p_origin_prod%3A) is a small, low-cost microcontroller that can be programmed to act as a USB Human Interface Device (HID), enabling automatic keyboard input for various automation tasks.

## Prerequisites

- Arduino IDE (1.8.x or later)
- ATTINY85 microcontroller

## Setup Instructions

### 1. Install Arduino IDE

Download and install the Arduino IDE from [arduino.cc](https://www.arduino.cc/en/software)

### 2. Add Board Manager URL

Open Arduino IDE and go to **File > Preferences**. In the "Additional Board Manager URLs" field, add this URL:

```
https://raw.githubusercontent.com/ArminJo/DigistumpArduino/master/package_digistump_index.json
```

### 3. Install Board Package

1. Go to **Tools > Board > Boards Manager**
2. Search for and install:
   - **Digistump AVR Boards** (by Digistump)

### 4. Configure Board Settings

1. Select **Tools > Board > Digistump AVR Boards > Digispark**

## Programming the ATTINY85

1. Once you are satisfied with your code, you can hit upload
2. Read the terminal for instructions where it will prompt you to enter plug in the board

**Note**: This project is for educational and automation purposes. Always test thoroughly before using in production environments.

### Demo
![Demo](assets/sample.gif)