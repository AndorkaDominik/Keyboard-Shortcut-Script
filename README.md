# AutoHotkey Script Setup for Windows

This guide explains how to set up an AutoHotkey script that automatically replaces the text "ddd" with your email address, and how to configure the script to run automatically when your computer starts.

## Prerequisites

- Windows operating system
- AutoHotkey installed (Download it from [AutoHotkey's official website](https://www.autohotkey.com/))

## Step-by-Step Guide

### 1. Creating the AutoHotkey Script

1. **Download and Install AutoHotkey:**
   - Visit the [AutoHotkey website](https://www.autohotkey.com/) and download the installer.
   - Follow the installation instructions.

2. **Create a New AutoHotkey Script:**
   - Right-click on your desktop.
   - Select **New > AutoHotkey Script**.
   - Name your script (e.g., `MyScript.ahk`).

3. **Edit the Script:**
   - Right-click the newly created script file.
   - Select **Edit Script**.

4. **Add the Shortcut:**
   - Insert the following line into the script:
     ```ahk
     ::ddd::example@gmail.com
     ```
   - This line sets up a shortcut that replaces "ddd" with "asd@gmail.com" when typed.

5. **Save and Run the Script:**
   - Save the script file.
   - Double-click the script to run it. The script will now be active, and typing "ddd" will automatically replace it with your email address.

### 2. Configuring the Script to Start Automatically

To ensure that your AutoHotkey script runs automatically every time you start your computer:

1. **Create the Script as Described Above:**
   - Follow the instructions in the previous section to create your AutoHotkey script.

2. **Add the Script to the Startup Folder:**
   - Press **Win + R** to open the **Run** dialog.
   - Type `shell:startup` and press **Enter**. This opens the **Startup** folder.
   - Copy your script file (e.g., `MyScript.ahk`) into this folder.

   After completing these steps, your script will automatically run every time you start your computer, ensuring that your custom shortcuts are always available.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

