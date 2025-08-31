# Minecraft Setup Guide for NeoForge with mods

Follow these steps to install and configure Minecraft with the NeoForge launcher on Windows.

---

## 1. Download and Install Minecraft Laucnher
👉 [Download Minecraft](https://www.minecraft.net/en-us/download)

Once the installation is completed, you need to run the laucher at least once before continuing

---

## 2. Download and Install Java (JDK 21)
You can just click next at every steps to install it in the default directory

👉 [Download Java JDK 21](https://www.oracle.com/java/technologies/downloads/#java21)

![alt text](bin/images/JAVA.png)

---

## 3. Download and Install NeoForge Launcher
👉 [Download NeoForge](https://neoforged.net/)

- a) Select the versions:
  - i) **Minecraft**: 1.21.7
  - ii) **Neoforge**: 21.7.25-beta
  - iii) Click on "Click here to download installer"
- b) Run the installer (you need Java from step 2 for this)
  - i) follow the instructions on the image

![alt text](bin/images/Neoforge.png)

---

## 4. Download mods folder

👉 [Download Mods.zip](https://github.com/BerubePascal/Minecraft/releases/tag/V1.21.7-1)

---

## 5. Install the mods
1) Launch Minecraft

    You should see the Noeforge launcher on the main page (See image)

    ![alt text](bin/images/Minecraft_launcher.png)

2) Open installations menu and follow the steps on the image
 
   ![alt text](bin/images/Installation.png)

3) Paste the mods folder in the directory

    If the folder already existe, overwrite it

---

## [Optionnal] 6. Allocate more RAM
Modded minecraft need a little more RAM then the default value

1) In the installations menu, go to "Edit"
    ![alt text](bin/images/RAM_1.png)

2) Click on "More options"
3) In the JVM Arguments, edit the numerical value in *-XmxYYG-* where *YY* is the RAM (here it's set to 16Go) 
    ![alt text](bin/images/RAM_2.png)