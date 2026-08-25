---
name: Desktop Issue
about: Desktop Issue related to Firmware/Software/Drivers
title: '[Desktop] '
labels: 'Desktop'
assignees: ''

---

## Device Information

### System Model or SKU

- [x] Framework Desktop (AMD Ryzen™ AI Max 300 Series)

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
* Port the Peripheral was connected to. Please see the following for port numbering: [Desktop](https://knowledgebase.frame.work/en_us/expansion-card-functionality-on-framework-desktop-amd-ryzen-ai-max-300-series-HyhiaJYVxl)
* Device or expansion card attached to the **Adjacent port** to the port that is having the issue.

1. [ Fill In device / expansion card ]
2. [ Fill In device / expansion card ]

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
