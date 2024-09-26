---
name: Laptop Issue
about: Laptop Issue related to Firmware/Software/Drivers
title: Laptop Issue
labels: ''
assignees: ''

---

## Device Information

### System Model or SKU

Please select one of the following

- [ ] Framework Laptop 13 (11th Gen Intel® Core™)
- [ ] Framework Laptop 13 (12th Gen Intel® Core™)
- [ ] Framework Laptop 13 (13th Gen Intel® Core™)
- [ ] Framework Laptop 13 (AMD Ryzen™ 7040 Series)
- [ ] Framework Laptop 13 (Intel® Core™ Ultra Series 1)
- [ ] Framework Laptop 16 (AMD Ryzen™ 7040 Series)

### BIOS VERSION
Please provide the bios version. 

Windows:
Open a command terminal as administrator:
```wmic bios get SMBIOSBIOSVERSION```

Linux: 
Open a terminal and run the following command
```sudo dmidecode --string bios-version```

### DIY Edition information
If you are experiencing an issue on a DIY system, Please also fill out the memory and storage devices you are using. 

Memory: Manufacture and SKU
Storage: Manufacture and SKU

### Port/Peripheral information
If you are experiencing an issue with a peripheral or an expansion card/port please fill out the following information: 
* Peripheral vendor and name.
* Port the Peripheral was connected to. Please see the following for port numbering: [Laptop 16](https://knowledgebase.frame.work/expansion-card-slot-functionality-on-framework-laptop-16-rkUjGm7cn) or [Laptop 13](https://knowledgebase.frame.work/expansion-card-functionality-on-framework-laptop-13-amd-ryzen-7040-series-SkrVx7gAh)
* Device or expansion card attached to the **Adjacent port** to the port that is having the issue.
1. [ Fill In device / expansion card ]
2. [ Fill In device / expansion card ]
3. [ Fill In device / expansion card ] 
4. [ Fill In device / expansion card ]

The following are for Laptop 16 only. 
5. [ Fill In device / expansion card ]
6. [ Fill In device / expansion card ]

### Standalone Operation
Are you running your mainboard as a standalone device. Is standalone mode enabled in the BIOS?
- [ ] Yes
- [ ] No

## Describe the bug
A clear and concise description of what the bug is.

## Steps To Reproduce
Steps to reproduce the behavior:
1. Go to '...'
2. Click on '....'
3. Scroll down to '....'
4. See error

## Expected behavior
A clear and concise description of what you expected to happen.

## Screenshots
If applicable, add screenshots to help explain your problem.

## Operating System (please complete the following information):
 - OS/Distribution: [e.g. Windows 11]
 - Version: [Version]
- Linux Kernel Version: `uname -a`

## Additional context
Add any other context about the problem here.
