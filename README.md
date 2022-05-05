# Windows XP X86 Drivers For HP Notebook 15

The HP 15 Notebook (Model g093sa) is a budget Laptop from Hewlett-Packard.
It was released around Jun 2, 2014 (from bios download date).

| Basic                   | Spec Sheet                                                                                                  |
|------------------------:|:-------------------------------------------------------                                                     |
| CPU                     | AMD A4-6210 (x86_64) 1.8ghz 4 cores (No Boost)                                                              |
| GPU                     | AMD Radeon R3 Graphics (No Working XP Drivers)                                                              |
| Sound                   | Dual Speakers                                                                                               |
| Keyboard                | Full-size island-style with numeric keypad                                                                  |                            |
| RAM                     | 4 GB DDR3 1600MHZ                                                                                           |
| Storage                 | 1TB 5400RPM SATA                                                                                            |
| Battery                 | Li-Ion 4-cell (41 WHr)                                                                                      |
| Dimensions              | 37.8 x 26 x 2.5 cm                                                                                          |
| Display                 | 15.6" diagonal HD BrightView LED-backlit (1366 x 768)                                                       |
| Weight                  | 2.23 KG                                                                                                     |
| Front camera            | HP TrueVision HD Webcam with integrated  microphone                                                         |
| Multimedia Drive        | SuperMulti DVD burner                                                                                       |
| External Ports          | 1 multi-format SD media card reader, 1 HDMI, 1 headphone/microphone combo, 2 USB 2.0, 1 USB 3.0, 1 RJ-45    |
| Network Card            | Integrated 10/100 BASE-T Ethernet LAN                                                                       |
| Wireless Connectivity   | 802.11b/g/n (1x1)                                                                                           |
| Shipped Windows Version | 8.1 Home                                                                                                    |

<img src="https://www.laptopsdirect.co.uk/Images/A2J5B54EA_1_Supersize.jpg?v=3" width="40%">

# Known Bugs

Any driver other than the SATA driver if loaded into nlite wont be installed in the system you'll have to install them via device manager, idk why.

THe graphics driver on the internet doesnt work and locks up the system on attempted installation

No ACPI Support (If anyone has any working ACPI driver for AMD systems please send)

Card reader driver either doesnt install or will make your system BSOD (presumably related to acpi?)

Ghost floppy disk controller (ACPI)

Sleep doesnt work (for obvious reasons)

# Installation tips

Upon boot of installation spam f5 until u get to a screen to select your pc type
Select Standard PC (This ignores any existance of ACPI so the laptop wont turn off in installation)
