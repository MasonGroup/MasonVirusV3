# MasonVirusV3

![MasonVirusV3](https://i.ibb.co/M8wvfjk/image.png)

## Overview

The **ABOLHB Virus** is a malicious program created by a developer known as **ABOLHB** from the **FREEMASONRY** group. This virus is designed to cause visual disturbances on the victim's screen by constantly inverting the colors in a random pattern, creating a chaotic and disorienting effect. It targets the desktop environment and utilizes GDI (Graphics Device Interface) functions to manipulate the display.

## What It Does

When executed, the virus continuously performs the following actions:

1. **Screen Distortion**: It uses the `PatBlt` function to invert the colors of the entire screen at random intervals, creating a glitchy, flickering effect. 🎨
2. **Randomized Colors**: The virus randomly generates RGB color values and applies them to the screen, making the visual effect unpredictable. 🌈
3. **Infinite Loop**: The program runs in an infinite loop, causing the screen to flicker indefinitely, making it nearly impossible for the user to work with their computer. 🔁

This virus runs silently in the background and can cause significant disruption to the user experience. It can be used as a prank or as part of a larger malicious attack.

## Technical Details

The virus is built using C# and leverages several Windows API functions, including:

- **`GetDesktopWindow`**: Retrieves a handle to the desktop window. 🖥️
- **`GetWindowDC`**: Retrieves the device context (DC) for the desktop window. 🖱️
- **`ReleaseDC`**: Releases the device context after use. 🔄
- **`GetSystemMetrics`**: Retrieves screen width and height for the current display. 📏
- **`CreateSolidBrush`**: Creates a solid brush with a random color. 🖌️
- **`SelectObject`**: Selects the brush into the device context. 🎨
- **`PatBlt`**: Performs a bit-block transfer (used here for inverting the screen colors). 🔲

The program runs indefinitely and causes the screen to flicker with random colors, disrupting normal usage.

## How to Compile

To compile this program, use a C# compiler such as Visual Studio. Once compiled, you can run the executable file, and the virus will start affecting the screen.

### Steps:
1. Open the code in Visual Studio or another C# IDE. 💻
2. Compile the code into an executable (`.exe`). ⚙️
3. Run the executable on a Windows machine. 🚀

## Disclaimer

**ABOLHB** and **FREEMASONRY** **do not take responsibility for any misuse of this code**. This software is a **malicious virus** designed to cause disruption and is intended for **educational purposes only**. It is **illegal and unethical** to use such programs without the explicit consent of the target user. ⚠️

By using this code, you acknowledge that:

- You are solely responsible for any actions taken with this software. 🛑
- You will not use this virus to harm others, cause damage to systems, or disrupt the normal operation of any network or device. 🚫
- You have obtained explicit permission from the owner of the system before running this program. ✅

**ABOLHB** and **FREEMASONRY** **do not condone the use of this virus for malicious purposes**. Use it responsibly and only in controlled environments where you have permission to do so. ⚠️

## Warning

Running this virus can cause significant disruptions to your system, and it may be difficult to stop without restarting your computer. Please be cautious and ensure you are aware of the consequences before executing this program. ⚠️

## License

This software is released under the **FREEMASONRY License**. Unauthorized use, distribution, or modification is prohibited. 🚫
