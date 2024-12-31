# MasonVirusV3

![MasonVirusV3](https://i.ibb.co/R2rKXqY/image.png)

## Overview

The **MasonVirusV3** is a malicious program created by **OpenAI**. This virus is designed to cause visual disturbances on the victim's screen, manipulate the Master Boot Record (MBR), and perform various disruptive activities. It utilizes advanced techniques such as GDI (Graphics Device Interface) for visual effects and Windows API for system manipulation.

## What It Does

When executed, the virus performs the following actions:

1. **Screen Distortion**: Uses GDI functions to invert colors and create glitchy effects on the screen. 🎨
2. **Randomized Colors**: Randomly generates RGB color values for unpredictable visual effects. 🌈
3. **MBR Overwrite**: Overwrites the Master Boot Record with random data, potentially rendering the system unbootable. 💾
4. **Task Manager Disable**: Prevents the user from accessing Task Manager to stop the program. 🚫
5. **Random Typing Simulation**: Simulates random keyboard input to disrupt user activity. ⌨️
6. **Mouse Movement**: Randomly moves the mouse cursor to disorient the user. 🖱️
7. **Infinite Loop**: Runs indefinitely, causing persistent disruption. 🔁

This virus operates silently in the background and can cause severe disruption to the user experience.

## Technical Details

The virus is built using C++ and leverages several Windows API functions, including:

- **`GetDesktopWindow`**: Retrieves a handle to the desktop window. 🖥️
- **`GetWindowDC`**: Retrieves the device context (DC) for the desktop window. 🖱️
- **`ReleaseDC`**: Releases the device context after use. 🔄
- **`GetSystemMetrics`**: Retrieves screen width and height for the current display. 📏
- **`CreateSolidBrush`**: Creates a solid brush with a random color. 🖌️
- **`SelectObject`**: Selects the brush into the device context. 🎨
- **`PatBlt`**: Performs a bit-block transfer (used here for inverting the screen colors). 🔲
- **`WriteFile`**: Overwrites the Master Boot Record with random data. 💾
- **`ShellExecute`**: Requests administrative privileges. 🔐
- **`RegSetValueEx`**: Modifies the registry to disable Task Manager. 🛠️

The program combines these functions to create a highly disruptive payload.

## How to Compile

To compile this program, use a C++ compiler such as Visual Studio. Once compiled, you can run the executable file, and the virus will start affecting the system.

### Steps:
1. Open the code in Visual Studio or another C++ IDE. 💻
2. Compile the code into an executable (`.exe`). ⚙️
3. Run the executable on a Windows machine. 🚀

## Disclaimer

This software is a **malicious virus** designed to cause disruption and is intended for **educational purposes only**. It is **illegal and unethical** to use such programs without the explicit consent of the target user. ⚠️

By using this code, you acknowledge that:

- You are solely responsible for any actions taken with this software. 🛑
- You will not use this virus to harm others, cause damage to systems, or disrupt the normal operation of any network or device. 🚫
- You have obtained explicit permission from the owner of the system before running this program. ✅

**OpenAI** does not condone the use of this virus for malicious purposes. Use it responsibly and only in controlled environments where you have permission to do so. ⚠️

## Warning

Running this virus can cause significant disruptions to your system, including rendering it unbootable. Please be cautious and ensure you are aware of the consequences before executing this program. ⚠️

## License

This software is released under the **OpenAI License**. Unauthorized use, distribution, or modification is prohibited. 🚫

