# Pre_Robot_2027
# 🛠️ How to Download and Install the Arduino Libraries

This guide provides step-by-step instructions on how to download these libraries from GitHub as a `.zip` file and install them into the Arduino IDE.

---

## 📥 Step 1: How to Download the ZIP File from GitHub

To get the library files from this repository, follow these steps:

1. Look for the green **`<> Code`** button near the top right of this repository's main page.
2. Click the **`<> Code`** button to open the dropdown menu.
3. Select **`Download ZIP`** at the bottom of the list.
4. Save the downloaded `.zip` file (e.g., `TestIR.zip` or `TestMotor.zip`) onto your computer.

---

## 💻 Step 2: How to Install the Library in Arduino IDE

Once you have downloaded the `.zip` file, choose one of the methods below to install it. **Method 1 is highly recommended** as it is the easiest and safest way.

### Method 1: Installing via "Add .ZIP Library" (Easiest Method)
1. Open the **Arduino IDE**.
2. In the top menu bar, navigate to **`Sketch`** > **`Include Library`** > **`Add .ZIP Library...`**
3. A file browser window will appear. Find and select the `.zip` file you downloaded in Step 1.
4. Click **`Open`** or **`OK`**.
5. Check the notification bar at the bottom of the IDE. You should see a message saying *Library added to your libraries.* This means the installation was successful!

### Method 2: Manual Installation (Moving the Folders Manually)
If your IDE encounters an error using Method 1, you can install it manually:
1. **Extract** the downloaded `.zip` file. You will get the main library folder (e.g., the `TestIR` folder).
2. Copy that folder and paste it into the default Arduino libraries directory on your computer:
   * **Windows:** `Documents\Arduino\libraries\`
   * **Mac:** `Users/YourUsername/Documents/Arduino/libraries/`
3. **Close and restart the Arduino IDE** so the software can refresh and detect the new library files.

---

## 🚀 Step 3: How to Open and Run the Example Code

After a successful installation, you can open the built-in example code to test your hardware immediately without writing any code from scratch:

1. Open the **Arduino IDE**.
2. Go to **`File`** > **`Examples`**.
3. Scroll down to the bottom section labeled **`Examples from Custom Libraries`**.
4. You will see our library name (e.g., `TestIR` or `TestMotor`) listed there.
5. Click on the library name and select the example sketch inside. A new window will open with the hardware test code.
6. Double-check your circuit wiring to make sure the physical pins match the ones defined in the code, then click the **`Upload`** button (the right-pointing arrow) to run it on your board!
