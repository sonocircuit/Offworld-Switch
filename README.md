# OFFWORLD/SWITCH

![DEVICE](https://github.com/sonoCircuits/Offworld-Switch/blob/master/OFFWORLD-SWITCH%20IMAGES/IMG_2401.jpg)

The OFFWORLD/SWITCH is a small device to switch the USB data lines of a device between two hosts (A and B).

I needed a small device to switch the usb connection between a Norns and Ansible. While designing I deceded to incorporate monome's idea of the [offworld-1 device](https://github.com/monome/offworld-1). A more appropriate name would be "WORLD/SELECTOR" as it only works as offworld when the jumper is in the center position.

## How to use
There are three miniUSB B connectors on the rear and one USB A connector on the side. The Datalines D+/D- of the USB A are switched between the two outer miniUSB B connectors (A and B) via switch. <br>
The center miniUSB B connector provides +5V only.

![Side Image](https://github.com/sonoCircuits/Offworld-Switch/blob/master/OFFWORLD-SWITCH%20IMAGES/OFSW_REAR.JPG)

The miniUSB connector powering the device connected to the USB A can be selected via jumper. <br>
Top position A, middle position PWR and bottom position B.

![Header Image](https://github.com/sonoCircuits/Offworld-Switch/blob/master/OFFWORLD-SWITCH%20IMAGES/OFSW_HEADER.JPG)

## Improvements

* replace the 6pin jumper with a three way switch. However, while testing, hotswiching the power source made Norns crash on several occations.

## Make your own

[Eagle files](https://github.com/sonoCircuits/Offworld-Switch/tree/master/OFFWORLD-SWITCH%20EAGLE%20FILES)

[Octopart BOM](https://octopart.com/bom-tool/UnnvVqt7)
