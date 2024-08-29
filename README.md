# DJControl Starlight CFW
The DJ Control starlight is based of the STM32F401RBT6, thus it's easy to develop CFW for it.

## Flashing new firmware
Hold down the Bass/Filter button while plugging in the USB Cable.   

> If it shows up as "Guillemot DFU Device", uninstall it and remove these folders:   
> ``C:\Program Files\Guillemot``   
> ``C:\Program Files\Guillemot``
> Then install the "STM32 BOOTLOADER" driver.   

You can now open STM32CubeProgrammer, select USB, select your DJControl Starlight and flash custom firmware. We advise you to back up the original firmware first.

## Developing custom firmware   
~~Examples of custom firmware are coming along side of the pinouts.~~ Unfortunately I have damaged my own controller during a gig, thus can no longer document it's inner workings 🙃


