# !! Do not flash this recovery in stock NothingOS !!

***NOTE***: This recovery is for custom ROMs that support recovery as vendor_boot only

***Depending on ROM, the recovery may or may not work, so please understand that once you flash the recovery and it does not work then ping me in telegram chat with your ROM name.***

### Things to do beforehand
  - If you're using Maitreya's recovery, reflash your original boot image from the ROM
  - Download and keep the recovery zip in your device/pendrive
  - Download and unzip the recovery zip in your pc
  - Upto date drivers & platform tools



  **NOTE - The zip includes a file called recovery.img which is the vendor_boot image**

  **If you miss any steps and things go south, don't come to me**

### How to flash recovery 
   1. Boot device to bootloader

   2. Flash the image using the command using pc

       `fastboot flash vendor_boot <path to image>`


   3. Reboot to recovery and flash the OrangeFox recovery zip
 
   4. If you had screen lock, enter the pin/password you used in the ROM


        ...that's it!

   5.  Alternatively if your custom ROM recovery has disabled signature check, simply sideload the recovery using adb sideload

### How to use recovery to flash ROMs

   1. Keep the recovery zip in your device/USBdrive

   2. Flash your ROM

   3. Flash the recovery zip in after flashing ROM

   4. Format data (if clean flashing)

### Things tested till now

   1. Flashing AOSPA/PenguinOS in recovery

   2. Flashing custom kernel zip

   3. Flashing magisk

   4. MTP/pendrive mount

   5. ADB sideload

### Things not tested till now

   1. Flashing recovery flashable zips

   At the time of writing this the following has been tested by myself...
