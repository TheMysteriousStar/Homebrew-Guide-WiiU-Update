.. Homebrew Guide documentation master file, created by
   sphinx-quickstart on Sun Jan 13 23:22:33 2019.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Exploits and You
================

Step 1: Running the Exploit
---------------------------

1. Go to `wiiuexploit.xyz` in your Wii U web browser
2. Press the "Run Exploit!" Button while holding the B Button

    * **Note:** This may take some tries till it works. Just repeat the whole process from Step 0 and hope for the best.
........

Step 2: Backing up your NAND
----------------------------

1. Select `Wii U Nand Dumper` in the Homebrew Channel.
2. You now have multiple options:

    * Dump your SLC: YES (512MB) (Wii U firmware)
    * Dump your SLCCMPT: YES (512MB) (vWii firmware and internal storage)
    * Dump your MLC: if your SD Card is larger than NAND (8GB on white consoles, 32GB on black ones) (Your internal storage including all games, DLC, etc.)
    * Dump your OTP: YES
    * Dump your SEEPROM: YES

........

Step 3: Installing PayloadLoader
------------------------------------

1. return to 'wiiuexploit.xyz'.
2. Press the "Run Exploit!" button while holding the X Button
3. select the "installer" environment and Press A to launch
4. Press the A button to check for an installation

   * It should now tell you that the PayloadLoader can be installed onto the Health and Safety Information app.

5. select "Install / Update" 
6. you will be asked if you want to install the PayloadLoader to Health and Safety. select "install:
7. after the installation finishes, press A to shut down the Wii U

........

Step 4: Autoboot Tiramisu (Optional)
-------------------------------------------------

Your setup currently requires you to launch the Health and Safety Infomation app every time you wish launch Homebrew. 
If you wish to have Tiramisu loaded at startup follow these steps
1. Power on the console, enter the Health and Safety Infomation app and hold X button
2. select the installer environment.
3. Press A to check for an installation
4. Select "Boot Options"
5. you will be asked if you wish to change the boot title. Select Switch to PayloadLoader
6. after the process finishes, press A to shutdown the console

........

Step 5: Finalizing Setup
-------------------------------------------------
this step will finalize the setup you have created

1. Turn on the Wii U and open the EnvironmentLoader
2. navigate to the "tiramisu" environment and press Y to make it your default environment. then launch it normally

   * you will probably get a giant red screen telling you aren't blocking updates properly. Press A to continue anyway.

3. on the Tiramisu Boot Selector. the Wii U Menu should already be selected, Press Y to set this as the default Boot Title

........

Accessing Homebrew
-------------------------------------------------
to access the Homebrew Launcher in Tiramisu simply open the Mii Maker. if you wish to use the Mii Maker normally and/or want to leave the Homebrew Lanucher 
press the home button and you will return to the normal Mii Maker. you can choose to install the Homebrew Launcher Channel (HBLC) however this is not recommended. 
