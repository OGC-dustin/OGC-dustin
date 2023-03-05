# OGC.Engineering
## Embedded System Consulting, Design, and Development

dustin < at > ogc.engineering

---
These repositories are focused on layered development intended to speed up prototyping and development of embedded systems

---
Suggested folder structure, each repository will include suggested folder in its name ogc-<folder_abbreviation>-<name>
    
    i.e. ogc-lib-os-ooda ( library for the operating system that uses an ooda loop as its main processing loop )
- OGC/
    - projects
    - deployments
    - software
        - applications
        - libraries
    - firmware
    - hardware
---

Configuration/Support files
- projects - ( typically company IP ) Each folder under the projects folder contain a collection of all files needed to fully define a project including documentation, designs, analysis tools, certifications, etc.
- deployments - ( typically company IP ) Each folder under the deployments folder contain all files/links needed to build a deployable image including IDE projects, makefiles, preinclude headers, etc.

Hardware independent source files
- software/applications - ( typically company IP ) Each folder under the applications folder includes the application(s) that guide device operations
- software/libraries - ( mix of company IP and general use libraries ) Each folder under the libraries folder provides support building blocks for device operations.  A few examples include communications protocols, log formatting and operating systems that provide main.c ( see examples )

Hardware dependent source files
- firmware - ( mix of company IP and general use drivers/chip support packages ) This folder includes manufacture supplies chip support files, and a mix of general and company IP drivers and abstraction folders/files.
- hardware - ( typically company IP ) Each folder under the hardware folder holds the physical definition header for a piece of hardware
---

Example projects available: ( TBD )