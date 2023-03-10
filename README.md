![image](https://i.imgur.com/pajdPod.png)


# !!! README !!!
- BY RUNNING THIS EXECUTABLE, YOU AGREE THAT THE CREATOR IS NOT RESPONSIBLE FOR ANY DAMAGES.

- BY VIEWING THIS REPOSITORY, YOU AGREE THAT YOU WILL NOT SPREAD THIS EXECUTABLE TO DAMAGE OTHER PEOPLE'S COMPUTERS.

- Thank you, have fun with this malware in a virtual machine.

# wininstall.exe
My homemade virus that 50% destroys the system! (+ GDI Payloads).

The original name for this was actually setup.exe but I always named my Windows install disks (flash ISO to USB) WININSTALL. Therefore, I named this wininstall.exe.

# What it does
It overwrites MBR very quickly on the start so that if anyone wants to remove this trojan, they can't. It also won't allow people to kill/terminate the process AS EVEN USING TASKKILL (via cmd.exe) or Task manager WILL STILL RESULT IN A BLUE SCREEN. This malware pretends as a Windows 7 installer (upgrade) but honestly I think the user interface is garbage. Then after 25 seconds, it will start destroying the screen and your EYES with a 0.75 delayed flashing colours (based on GDI). It is also supposed to encrypt all text files in system32 folder but it dosen't seem to work.

# Language I used
- C#

- .NET Framework 4.7.2

- WinForms

# Credits
https://www.youtube.com/@ClutterTech - For GDI payloads
https://www.youtube.com/watch?v=XiTzsh1hErI - For C# anti kill source code
https://www.youtube.com/@Lewis.Channel - Planner, bug fixer, creator and more
Visual Studio 2022 - IDE
C# - The code language I used
Stock images - for Windows 7 images, install now, more user interface
