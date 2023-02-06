# Hackintosh EFI
This is the EFI currently in use on my system.

## Main Software
* OpenCore 0.8.8 (release and debug work)
* macOS 12.6.2 (*Ventura does not currently work until airportitlwm v2.2.0 stable*)

## Additional Software
* [AMD Power Gadget](https://github.com/trulyspinach/SMCAMDProcessor)
* [RadeonGadget](https://github.com/aluveitie/RadeonSensor) 
* [MonitorControl](https://github.com/MonitorControl/MonitorControl)

## Hardware
| Hardware     | Model                      |
|--------------|----------------------------|
| CPU          | AMD Ryzen 7 2700X          |
| Motherboard  | MSI B450I Gaming Plus AC   |
| GPU          | AMD Radeon RX 5700 XT      |
| RAM          | 32GB DDR4 @ 3200MHz (2x16) |
| Audio        | Realtek (ALC887), DP audio |
| WiFi/BT      | Intel AC-3168              |
| Ethernet     | Realtek, currently broken  |
| Boot drive   | 256GB M.2 SATA SSD         |

## What doesn't work so far
* Ethernet as of yet, unable to get RealtekRTL8111 to work (across several versions, 2.2-2.4)
* Mic in, albeit this is a common issue on AppleALC with Ryzen systems

## What should be adjusted
* Redo the USB map for your system, I have mapped mine in accordance to my system (which has a broken USB port on the motherboard)
* Probably the audio codec. I don't use anything other than DisplayPort audio, as such ALC codecs are less of an issue
