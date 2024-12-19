# !! Do not flash this recovery in stock NothingOS !!


***At the time of writing this the following has been tested by myself***


 ## Things to do beforehand

  - Download and keep the recovery zip in your device/pendrive
  - Download and unzip the recovery zip in your pc

  **NOTE - The zip includes a file called recovery.img which is the vendor_boot image**

  **If you miss any steps and things go south, don't come to me**

 - How to flash recovery 
   1. Boot device to bootloader
  
   2. Flash the image using the command
  

       `fastboot flash vendor_boot <path to image>`
   3. Reboot to recovery and flash the OrangeFox recovery zip
   
        ...that's it!

 - How to use recovery to flash ROMs
   1. Keep the recovery zip in your device/USBdrive

  
   2. Flash your ROM
  

   3. Flash the recovery zip in after flashing ROM

   4. Format data (if clean flashing)

 - Things tested till now
   1. Flashing AOSPA/PenguinOS in recovery
   2. Flashing custom kernel zip

 - What is working 
   1. Charging
   2. Decryption
   3. Screenshot
   4. Logging
   5. MTP/pendrive mount


 - Things not tested till now
   1. Flashing magisk
   2. Flashing recovery flashable zips
   3. ADB sideload
