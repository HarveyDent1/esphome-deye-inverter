# Modbus Address Mapping - Deye Hybrid 3P

## Overview
This document contains all Modbus addresses used in ESPHome configuration for Deye Hybrid 3P inverter, sorted from smallest to largest address.

## Address Mapping

| Address | Entity Name | File | Type |
|---------|-------------|------|------|
| 0 | Device Inverter Modbus Address (Internal) | device.yaml | sensor |
| 1 | Device Modbus Address | device.yaml | sensor |
| 2 | Device Device Type | device.yaml | sensor |
| 3 | Device Rated Power | device.yaml | sensor |
| 10 | Device MPPT Number | device.yaml | sensor |
| 11 | Device Control Board Firmware Raw 11 | device.yaml | sensor |
| 12 | Device Serial Number 1 | device.yaml | sensor |
| 13 | Device Serial Number 2 | device.yaml | sensor |
| 14 | Device Control Board Firmware Raw 14 | device.yaml | sensor |
| 15 | Device Control Board Firmware Raw 15 | device.yaml | sensor |
| 16 | Device Communication Board Firmware Raw 16 | device.yaml | sensor |
| 17 | Device Communication Board Firmware Raw 17 | device.yaml | sensor |
| 18 | Device Communication Board Firmware Raw 18 | device.yaml | sensor |
| 20 | Device Rated Power | device.yaml | sensor |
| 22 | Device MPPTs / Device Phases | device.yaml | sensor |
| 36 | Device Model Number | device.yaml | sensor |
| 61 | Device Country/Region Code | device.yaml | sensor |
| 62 | Inverter Date Time Raw 1 | device.yaml | sensor |
| 63 | Inverter Date Time Raw 2 | device.yaml | sensor |
| 64 | Inverter Date Time Raw 3 | device.yaml | sensor |
| 80 | Power Switch | device.yaml | switch |
| 98 | Battery Control Mode | battery.yaml | select |
| 99 | Battery Equalization Voltage | battery.yaml | number |
| 100 | Battery Absorption Voltage | battery.yaml | number |
| 101 | Battery Float Voltage | battery.yaml | number |
| 102 | Battery Capacity | battery.yaml | number |
| 103 | Battery Empty Voltage | battery.yaml | number |
| 104 | Zero Export Power | work_mode.yaml | number |
| 105 | Battery Equalization Cycle | battery.yaml | number |
| 106 | Battery Equalization Time | battery.yaml | number |
| 107 | Battery Temperature Compensation | battery.yaml | number |
| 108 | Maximum Battery Charge Current | battery.yaml | number |
| 109 | Maximum Battery Discharge Current | battery.yaml | number |
| 111 | Battery Operation Mode | battery.yaml | select |
| 112 | Battery Wake Up / Battery 2 Wake Up | battery.yaml | switch |
| 113 | Battery Resistance | battery.yaml | number |
| 114 | Battery Charging Efficiency | battery.yaml | number |
| 115 | Battery Shutdown SOC | battery.yaml | number |
| 116 | Battery Restart SOC | battery.yaml | number |
| 117 | Battery Low SOC | battery.yaml | number |
| 118 | Battery Shutdown Voltage | battery.yaml | number |
| 119 | Battery Restart Voltage | battery.yaml | number |
| 120 | Battery Low Voltage | battery.yaml | number |
| 121 | Generator Operating Time | gen.yaml | number |
| 122 | Generator Cooling Time | gen.yaml | number |
| 123 | Battery Generator Charging Start Voltage | battery.yaml | number |
| 124 | Battery Generator Charging Start SOC | battery.yaml | number |
| 125 | Battery Generator Charging Current | battery.yaml | number |
| 126 | Battery Grid Charging Start Voltage | battery.yaml | number |
| 127 | Battery Grid Charging Start SOC | battery.yaml | number |
| 128 | Maximum Battery Grid Charge Current | battery.yaml | number |
| 129 | Battery Generator Charging | battery.yaml | switch |
| 130 | Battery Grid Charging | battery.yaml | switch |
| 132 | Generator Turn Off SOC | gen.yaml | number |
| 133 | Generator Port Use | gen.yaml | select |
| 134 | SmartLoad Off Voltage | gen.yaml | number |
| 135 | SmartLoad Off SOC | gen.yaml | number |
| 136 | SmartLoad On Voltage | gen.yaml | number |
| 137 | SmartLoad On SOC | gen.yaml | number |
| 138 | Grid Voltage | grid.yaml | number |
| 139 | PV Minimum Power To Start Generator | gen.yaml | number |
| 140 | Charging Signal | grid.yaml | binary_sensor |
| 141 | Energy Management Priority | work_mode.yaml | select |
| 142 | System Work Mode | work_mode.yaml | select |
| 143 | Sell First | work_mode.yaml | switch |
| 145 | AC Couple On Grid Side | work_mode.yaml | binary_sensor |
| 146 | Load Priority Time of Use | tou.yaml | select |
| 148 | Time of Use 1 Start | tou.yaml | select |
| 149 | Time of Use 2 Start | tou.yaml | select |
| 150 | Time of Use 3 Start | tou.yaml | select |
| 151 | Time of Use 4 Start | tou.yaml | select |
| 152 | Time of Use 5 Start | tou.yaml | select |
| 153 | Time of Use 6 Start | tou.yaml | select |
| 154 | Time of Use 1 Out Power | tou.yaml | number |
| 155 | Time of Use 2 Out Power | tou.yaml | number |
| 156 | Time of Use 3 Out Power | tou.yaml | number |
| 157 | Time of Use 4 Out Power | tou.yaml | number |
| 158 | Time of Use 5 Out Power | tou.yaml | number |
| 159 | Time of Use 6 Out Power | tou.yaml | number |
| 160 | Time of Use 1 Charge Power | tou.yaml | number |
| 161 | Time of Use 2 Charge Power | tou.yaml | number |
| 162 | Time of Use 3 Charge Power | tou.yaml | number |
| 163 | Time of Use 4 Charge Power | tou.yaml | number |
| 164 | Time of Use 5 Charge Power | tou.yaml | number |
| 165 | Time of Use 6 Charge Power | tou.yaml | number |
| 166 | Time of Use 1 SOC | tou.yaml | number |
| 167 | Time of Use 2 SOC | tou.yaml | number |
| 168 | Time of Use 3 SOC | tou.yaml | number |
| 169 | Time of Use 4 SOC | tou.yaml | number |
| 170 | Time of Use 5 SOC | tou.yaml | number |
| 171 | Time of Use 6 SOC | tou.yaml | number |
| 172 | Time of Use 1 Enabled | tou.yaml | switch |
| 173 | Time of Use 2 Enabled | tou.yaml | switch |
| 174 | Time of Use 3 Enabled | tou.yaml | switch |
| 175 | Time of Use 4 Enabled | tou.yaml | switch |
| 176 | Time of Use 5 Enabled | tou.yaml | switch |
| 177 | Time of Use 6 Enabled | tou.yaml | switch |
| 178 | Generator / System Work Mode / Smart Load Control / Multiple Select | work_mode.yaml/gen.yaml | various |
| 179 | Remote Lock | grid.yaml | switch |
| 183 | Grid Frequency | grid.yaml | sensor |
| 189 | Auto Return To Grid | grid.yaml | switch |
| 190 | Start PV Power | gen.yaml | number |
| 191 | Sync Grid On | work_mode.yaml | switch |
| 210 | Battery BMS Charging Voltage | battery.yaml | sensor |
| 211 | Battery BMS Discharging Voltage | battery.yaml | sensor |
| 212 | Battery BMS Charging Current | battery.yaml | sensor |
| 213 | Battery BMS Discharging Current | battery.yaml | sensor |
| 214 | Battery BMS SOC | battery.yaml | sensor |
| 215 | Battery BMS Voltage | battery.yaml | sensor |
| 216 | Battery BMS Current | battery.yaml | sensor |
| 218 | Battery BMS Max Charging Current | battery.yaml | sensor |
| 219 | Battery BMS Max Discharging Current | battery.yaml | sensor |
| 220 | Battery Alarm | battery.yaml | binary_sensor |
| 221 | Battery Fault | battery.yaml | binary_sensor |
| 222 | Battery BMS Other Symbol | battery.yaml | sensor |
| 223 | Battery BMS Type | battery.yaml | select |
| 234 | AC Couple | grid.yaml | number |
| 237 | Maximum Grid Voltage | grid.yaml | number |
| 340 | External PV Control | work_mode.yaml | switch |
| 341 | PV MPPT Mode | pv.yaml | select |
| 500 | Device Information | device.yaml | sensor |
| 514 | Daily Battery Charge | battery.yaml | sensor |
| 515 | Daily Battery Discharge | battery.yaml | sensor |
| 516 | Total Battery Charge | battery.yaml | sensor |
| 518 | Total Battery Discharge | battery.yaml | sensor |
| 520 | Daily Energy Bought | grid.yaml | sensor |
| 521 | Daily Energy Sold | grid.yaml | sensor |
| 522 | Total Energy Bought | grid.yaml | sensor |
| 524 | Total Energy Sold | grid.yaml | sensor |
| 526 | Daily Load Consumption | load.yaml | sensor |
| 527 | Total Consumption | load.yaml | sensor |
| 529 | Daily PV Production | pv.yaml | sensor |
| 534 | Total PV Production | pv.yaml | sensor |
| 536 | Daily Generator Production | gen.yaml | sensor |
| 537 | Total Generator Production | gen.yaml | sensor |
| 540 | DC Temperature | inverter.yaml | sensor |
| 541 | AC Temperature | inverter.yaml | sensor |
| 548 | Communications Board Failure Status | device.yaml | sensor/binary_sensor |
| 551 | Turn Off/On Status | device.yaml | binary_sensor |
| 552 | Microinverter Power / Load Power / Generator Power / Total Power | various | sensor |
| 553 | Solar Sell | device.yaml | binary_sensor |
| 555 | Error Code / Device Operating Status | device.yaml | text_sensor |
| 586 | Battery Temperature | battery.yaml | sensor |
| 587 | Battery Voltage | battery.yaml | sensor |
| 588 | Battery | battery.yaml | sensor |
| 589 | Battery 2 | battery.yaml | sensor |
| 590 | Battery Power | battery.yaml | sensor |
| 591 | Battery Current | battery.yaml | sensor |
| 592 | Battery Corrected Capacity | battery.yaml | sensor |
| 593 | Battery 2 Voltage | battery.yaml | sensor |
| 594 | Battery 2 Current | battery.yaml | sensor |
| 595 | Battery 2 Power | battery.yaml | sensor |
| 596 | Battery 2 Temperature | battery.yaml | sensor |
| 597 | Grid Current | grid.yaml | sensor |
| 598 | Grid L1 Voltage | grid.yaml | sensor |
| 599 | Grid L2 Voltage | grid.yaml | sensor |
| 600 | Grid L3 Voltage | grid.yaml | sensor |
| 604 | Internal CT L1 Power Low | grid.yaml | sensor |
| 605 | Internal CT L2 Power Low | grid.yaml | sensor |
| 606 | Internal CT L3 Power Low | grid.yaml | sensor |
| 607 | Internal CT Power Low | grid.yaml | sensor |
| 609 | Grid Frequency | grid.yaml | sensor |
| 610 | Grid L1 Current | grid.yaml | sensor |
| 611 | Grid L2 Current | grid.yaml | sensor |
| 612 | Grid L3 Current | grid.yaml | sensor |
| 613 | Grid Current | grid.yaml | sensor |
| 614 | Grid Power Factor | grid.yaml | sensor |
| 615 | Grid Frequency | grid.yaml | sensor |
| 616 | External CT L1 Power Low | grid.yaml | sensor |
| 617 | External CT L2 Power Low | grid.yaml | sensor |
| 618 | External CT L3 Power Low | grid.yaml | sensor |
| 619 | External CT Power Low | grid.yaml | sensor |
| 621 | Grid Power Factor | grid.yaml | sensor |
| 622 | Grid L1 Power Low | grid.yaml | sensor |
| 623 | Grid L2 Power Low | grid.yaml | sensor |
| 624 | Grid L3 Power Low | grid.yaml | sensor |
| 625 | Grid Power Low | grid.yaml | sensor |
| 627 | Output L1 Voltage | inverter.yaml | sensor |
| 628 | Output L2 Voltage | inverter.yaml | sensor |
| 629 | Output L3 Voltage | inverter.yaml | sensor |
| 630 | Output L1 Current | inverter.yaml | sensor |
| 631 | Output L2 Current | inverter.yaml | sensor |
| 632 | Output L3 Current | inverter.yaml | sensor |
| 633 | Output L1 Power Low | inverter.yaml | sensor |
| 634 | Output L2 Power Low | inverter.yaml | sensor |
| 635 | Output L3 Power Low | inverter.yaml | sensor |
| 636 | Output Power Low | inverter.yaml | sensor |
| 638 | Output Frequency | inverter.yaml | sensor |
| 640 | UPS L1 Power Low | load.yaml | sensor |
| 641 | UPS L2 Power Low | load.yaml | sensor |
| 642 | UPS L3 Power Low | load.yaml | sensor |
| 643 | UPS Power Low | load.yaml | sensor |
| 644 | Load L1 Voltage | load.yaml | sensor |
| 645 | Load L2 Voltage | load.yaml | sensor |
| 646 | Load L3 Voltage | load.yaml | sensor |
| 650 | Load L1 Power Low | load.yaml | sensor |
| 651 | Load L2 Power Low | load.yaml | sensor |
| 652 | Load L3 Power Low | load.yaml | sensor |
| 653 | Load Power Low | load.yaml | sensor |
| 655 | Load Power | load.yaml | sensor |
| 656 | Load L1 Power High | load.yaml | sensor |
| 657 | Load L2 Power High | load.yaml | sensor |
| 658 | Load L3 Power High | load.yaml | sensor |
| 659 | Load Power High | load.yaml | sensor |
| 661 | Generator L1 Voltage | gen.yaml | sensor |
| 662 | Generator L2 Voltage | gen.yaml | sensor |
| 663 | Generator L3 Voltage | gen.yaml | sensor |
| 664 | Generator Frequency | gen.yaml | sensor |
| 665 | Generator L1 Power Low | gen.yaml | sensor |
| 666 | Generator L2 Power Low | gen.yaml | sensor |
| 667 | Generator L3 Power Low | gen.yaml | sensor |
| 668 | Generator L1 Current | gen.yaml | sensor |
| 669 | Generator L2 Current | gen.yaml | sensor |
| 670 | Generator L3 Current | gen.yaml | sensor |
| 671 | Generator Total Power Low | gen.yaml | sensor |
| 672 | PV1 Power | pv.yaml | sensor |
| 673 | PV2 Power | pv.yaml | sensor |
| 674 | PV3 Power | pv.yaml | sensor |
| 675 | PV4 Power | pv.yaml | sensor |
| 676 | PV1 Voltage | pv.yaml | sensor |
| 677 | PV1 Current | pv.yaml | sensor |
| 678 | PV2 Voltage | pv.yaml | sensor |
| 679 | PV2 Current | pv.yaml | sensor |
| 680 | PV3 Voltage | pv.yaml | sensor |
| 681 | PV3 Current | pv.yaml | sensor |
| 682 | PV4 Voltage | pv.yaml | sensor |
| 683 | PV4 Current | pv.yaml | sensor |
| 687 | Grid L1 Power High | grid.yaml | sensor |
| 688 | Grid L2 Power High | grid.yaml | sensor |
| 689 | Grid L3 Power High | grid.yaml | sensor |
| 690 | Grid Power High | grid.yaml | sensor |
| 691 | Output L1 Power High | inverter.yaml | sensor |
| 692 | Output L2 Power High | inverter.yaml | sensor |
| 693 | Output L3 Power High | inverter.yaml | sensor |
| 694 | Output Power High | inverter.yaml | sensor |
| 696 | UPS L1 Power High | load.yaml | sensor |
| 697 | UPS L2 Power High | load.yaml | sensor |
| 698 | UPS L3 Power High | load.yaml | sensor |
| 699 | UPS Power High | load.yaml | sensor |
| 700 | Internal CT L1 Power High | grid.yaml | sensor |
| 701 | Internal CT L2 Power High | grid.yaml | sensor |
| 702 | Internal CT L3 Power High | grid.yaml | sensor |
| 703 | Internal CT Power High | grid.yaml | sensor |
| 705 | External CT L1 Power High | grid.yaml | sensor |
| 706 | External CT L2 Power High | grid.yaml | sensor |
| 707 | External CT L3 Power High | grid.yaml | sensor |
| 708 | External CT Power High | grid.yaml | sensor |