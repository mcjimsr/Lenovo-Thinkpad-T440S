# Lenovo-Thinkpad-T440S (forked from Sniki)
This repo is used to create a working Hackintosh with a Lenovo ThinkPad T440S. All files were complied or created by Sniki and I have made only minor modificaitons.

# To complete the build, please refer to this guide.
https://www.tonymacx86.com/threads/guide-lenovo-thinkpad-t440s-using-clover-uefi-hotpatch.279492/

# Compatible WiFi Cards (from Sniki, not me)
The Intel Wireless and Bluetooth card that comes with this laptop is not supported, therefore a replacement is necessary in order to have working Wireless and Bluetooth. Some compatible replacement cards are:

DW1830: This card has 802.11AC Dual Band Wireless Support and Bluetooth 4.1 LE and it should be cheaper than the DW1560 model, the other advantage is that it has native ID(s) which works out of the box in macOS.
The only downside is that it has 3 antenna connectors and T440S does have only two antennas.
That shouldn't be a hard workaround as you can order an antenna from AliExpress for super cheap price or just use the two connectors and leave one empty as people reported having it working correctly even like that.

DW1560: This card has 802.11AC Dual Band Wireless Support and Bluetooth 4.0 LE it recently became more expensive which i think is due to the fact that the number of existing cards is being reduced thus becoming rare.

BCM94360CS2: This card is the one available on real Macbook and Macbook Pro and has two antenna connectors.
It needs the NGFF adapter in order to be able to use it in our laptops that have NGFF slots if there is enough room or space to fit it without getting in the way for the cover or any other part of the laptop.
(Haven't tested because i don't have this laptop anymore, web pictures of laptop interior show that there should be enough room to fit it, you may only need to trim or cut the last part of the NGFF adapter to fit it perfectly)
Note: BCM94360CS2 is natively fully supported on macOS without using any kext at all wether for WiFi or Bluetooth.
All features like HandOff, Continuity, Instant Hotspot, Universal Clipboard should work without a single issue.

DW1820A: This card has also been flying under the radar recently on many forums and seems to work well.
Note: be careful and only pick the model from the link that i attached as the other models with different IDs seem to have issues with kernel panics and random disconnects, the one i attached on the link is the correct one.
The model that you should look for is the one with the part number: CN-0VW3T3
The two other variants with part number starting with: CN-096JNT and CN-08PKF4 seems to be problematic.

