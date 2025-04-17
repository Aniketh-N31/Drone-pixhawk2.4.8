This is my quadcopter project using Pixhawk 2.4.8
# Drone Using Pixhawk 2.4.8

This is my drone project using Pixhawk 2.4.8 flight controller.

## 🔩 Components:
- Pixhawk 2.4.8
- FS-i6X Transmitter + FS-iA10B Receiver
- F450 Frame
- 1400KV Motors with 9" Propellers
- BLHeli 30A ESCs
- NEO-7M GPS
- Power Module, Safety Switch & Buzzer

## 🔧 Procedure:
- Assemble the F450 frame
- Mount BLDC motors and connect ESCs
- Solder to PDB and connect Power Module
- Connect GPS, Buzzer, and Safety Switch
- Attach propellers correctly
- Calibrate everything using Mission Planner

## ⚠️ Issues Faced and Fixes:
| Issue | Fix |
|-------|-----|
| Calibration Error | Flat surface, stay away from metal |
| GPS Lock Issue | Test outside, check wiring |
| ESC not syncing | Use Mission Planner calibration |
| Drone flipping | Check motor order & direction |
| Failsafe Trigger | Check battery and GPS health |
| Not Arming | Check pre-arm messages and safety switch |

📄 Full Documentation in `Drone using pixhawk 2.4.8.docx`
