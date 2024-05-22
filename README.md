[ VisualBGRT Bootloader Utility for UEFI-based Windows Systems Read Me ]

==================================================================

[ About ]

- Version 1.1.0
- Microsoft .NET Framework Version 4.8
- Developed by Josué Beauregard
- EFI Bootloader developed by Lauri Kenttä (Metabolix) from GitHub
- User Interface written in Visual Basic .NET
- EFI Bootlader written in C

==================================================================

[ Description ]

Based from HackBGRT made by Metabolix from GitHub, you can customize your own Windows logo with MSPaint and setting up on the UEFI system
using this simple console app. But with VisualBGRT, you can select your own logo from any image formats (e.g BMP, PNG, JPEG) then
modify the size using this very useful Graphical User Interface (GUI) and now including an embedded preview screen that which size and position of
the logo will be configured inside the screen. Furthermore, you can actually instantly update the size of the logo visually like "Magic" and then you
can also fit your logo into full screen which will match the screen resolution. Within any image formats, they will automatically converted into 24-Bit Bitmap
after the custom boot screen is installed as the PNG format, the transparent background will drawn black. There's 4 types that you can select one
for the installation (Defaults [Firmware, Native], Custom Logo or without the logo [Black Logo]). If you'd like that Windows will show your custom
logo while booting, you can select Custom Logo in the GUI as well. If you encountered unbootable after you messed up the installation, use the
Windows Installation Media, restart your computer and then execute the Startup Repair from the Troubleshoot section.

On Windows 11, you can enable the new loading animation included.

This utility application is absolutely freeware and easy to use and intended for both beginner and advanced users.

You can find more information about HackBGRT on GitHub: https://github.com/Metabolix/HackBGRT

==================================================================

[ Requirements ]

- Operating Systems: Windows 8/8.1, 10 and 11 (64-Bit and 32-Bit)
- BIOS: UEFI-based System (Recommended Secure Boot Disabled)
- Prerequisites: Microsoft .NET Framework 4.8

[ Cross-Compilers and Librairies are used for compiling the EFI bootloader ]

- GCC targeting w64-mingw32 (x86_64-w64-mingw32-gcc, i686-w64-mingw32-gcc)
- GNU Linker (GNU Binutils)
- GNU Make
- mingw-w64-gnu-efi

- The bootloader has been compiled from ArchLinux under Windows Subsystem for Linux

==================================================================

[ Installation ]

1. Start the utility (Always provide as Administrator), if UEFI is detected on your computer, it will verify if the EFI System Partition exists then open the interface.

2. Select any types of boot you want to customize.

3. For Custom Logo, select any image file in any formats, change the size from the drop-down box or customize with sliders.

4. Preview your custom boot screen, if you want to change the size of the logo instantly inside the preview, press the S key to do it.

5. If is all set to go, click Install Bootloader to start the installation, however it shows a warning message that before you install the new logo to prevent unbootable, you can enable Debug Mode before booting.

6. After the installation complete, it will show a message with the list of results if is installed.

7. If you'd like to test your new logo, restart your computer and boot it to see the effective change of the new logo. You can also enable Debug Mode as well.

8. If you encountered unbootable after starts up, use the Windows Installation Media, restart your computer and then execute the Startup Repair from the Troubleshoot section.

==================================================================
