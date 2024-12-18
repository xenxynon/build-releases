# !! Do not flash this recovery in stock NothingOS !!


***At the time of writing this the following has been tested by myself***


 ## Things to do beforehand

  - Download and unzip the recovery zip in your device
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
   1. Keep the recovery.img in your device
  
   2. Flash your ROM
  

   4. Flash the `recovery.img` in vendor boot partition
   
      (Swipe down if you can't see vendor boot option)

 - Things tested till now
   1. Flashing AOSPA/PenguinOS in recovery

 - What is working 
   1. Charging
   2. Decryption
   3. Screenshot
   4. Logging

 - Things not tested till now
   1. Flashing magisk
   2. MTP
   3. Flashing recovery flashable zips
   4. ADB sideload
