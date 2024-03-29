<img src="../../../images/MORALAB_Banner.png">

# Installing Oracle VM VirtualBox
<br>

> The following are the instructions to install a virtual machine in **Windows 10** (now referred as the "host" operative system). The chosen virtual machine is **VirtualBox 6.1.18** and the system we will add "inside" the VM will be the **CentOS-Stream-8** Linux system (now referred as the "guest" operative system), but a similar process can be followed for other host and guest OS.

## - Downloads
<br>

> 1. Download VirtualBox from their website: [Download](https://download.virtualbox.org/virtualbox/6.1.18/VirtualBox-6.1.18-142142-Win.exe).

> 2. Download the ISO file with our guest OS (CentOS-Stream-8). You can find your favorite mirror site here: [Mirror sites](http://isoredirect.centos.org/centos/8-stream/isos/x86_64/). For this tutorial, we have downloaded our OS from here: [Download](http://download.nus.edu.sg/mirror/centos/8-stream/isos/x86_64/CentOS-Stream-8-x86_64-20210402-dvd1.iso).

## - Installing VirtualBox
<br>

> 3. Run VirtualBox installation file. After running, you will receive a welcome message giving start to the installation process.

<br>
<img src="images/VBox01.PNG" width="400">
<br>

> 4. Choose your desired location and other options.

<br>
<img src="images/VBox02.PNG" width="400">
<br>
<img src="images/VBox03.PNG" width="400">
<br>
<img src="images/VBox04.PNG" width="400">
<br>
<img src="images/VBox05.PNG" width="400">
<br>

> 5. After this, VirtualBox will be installed.

<br>
<img src="images/VBox06.PNG" width="400">
<br>
<img src="images/VBox07.PNG" width="400">
<br>

## - Creating a new Virtual Machine
<br>

> 6. To create a new VM, click on **"New"** and choose a name, folder, and operative system to be installed.

<br>
<img src="images/VBox11.PNG" width="400">
<br>

> 7. Define your desired memory and hard-disk specifications. Here we have chosen 8 GB memory and 40 GB hard disk.

<br>
<img src="images/VBox12.PNG" width="400">
<br>
<img src="images/VBox13.PNG" width="400">
<br>
<img src="images/VBox14.PNG" width="400">
<br>
<img src="images/VBox15.PNG" width="400">
<br>
<img src="images/VBox16.PNG" width="400">
<br>

> 8. After this, your first Virtual Machine will be created.

<br>
<img src="images/VBox17.PNG" width="400">
<br>

> 9. Optional: To improve the video memory, go to **Settings**, **Display**, and **Screen**. Here we raised the video memory from the specified value to 128 MB.

<br>
<img src="images/VBox18.PNG" width="400">
<br>

## - Installing CentOS-8
<br>

> 10. Now we can proceed to install the OS for our new VM: First, click on the new VM and the "Select startup disk" window will be opened. Then click on the small folder icon to get the "Optical disk selector" window, and, finally, click on "Create" and select the downloaded ISO file.

<br>
<img src="images/VBox19.PNG" width="400">
<br>
<img src="images/VBox20.PNG" width="400">
<br>
<img src="images/VBox21.PNG" width="400">
<br>
<img src="images/VBox22.PNG" width="400">
<br>

> 11. Press **Start** and the installation process will begin.

<br>
<img src="images/VBox23.PNG" width="400">
<br>

> 12. Choose language and installation destination (hard disk).

<br>
<img src="images/VBox24.PNG" width="400">
<br>
<img src="images/VBox25.PNG" width="400">
<br>
<img src="images/VBox26.PNG" width="400">
<br>

> 13. Choose the base environment and additional software. We select a **"Workstation"** with GNOME, Internet, Office, and Development applications, but CentOS offers other possibilities such as servers and servers with GUI.

<br>
<img src="images/VBox27.PNG" width="400">
<br>

> 14. Choose time/date and password, and you are ready to start installing CentOS.

<br>
<img src="images/VBox28.PNG" width="400">
<br>
<img src="images/VBox29.PNG" width="400">
<br>
<img src="images/VBox30.PNG" width="400">
<br>

> 15. Press **"Begin installation"** and reboot after the process is finished.

<br>
<img src="images/VBox32.PNG" width="400">
<br>

> 16. Accept the license agreement.

<br>
<img src="images/VBox33.PNG" width="400">
<br>
<img src="images/VBox34.PNG" width="400">
<br>
<img src="images/VBox35.PNG" width="400">
<br>

> 17. Click on **Finish configuration**, and choose your privacy options.

<br>
<img src="images/VBox37.PNG" width="400">
<br>

> 18. Finally, select your username and password.

<br>
<img src="images/VBox38.PNG" width="400">
<br>
<img src="images/VBox39.PNG" width="400">
<br>
<img src="images/VBox40.PNG" width="400">
<br>

> 19. CentOS-8 is ready to be used inside the VirtualBox. However, you might find annoying that the resolution is low, the screen size stays small even if you maximize, and other details, so the next step is advised.

<br>
<img src="images/VBox41.PNG" width="400">
<br>

## - Installing CentOS-8 Guest Additions
<br>

> 20. Inside CentOS, go to **Devices**, **Insert Guest Additions CD image**, and follow the procedure.

<br>
<img src="images/VBox47.PNG" width="400">
<br>
<img src="images/VBox48.PNG" width="400">
<br>
<img src="images/VBox49.PNG" width="400">
<br>
<img src="images/VBox50.PNG" width="400">
<br>
<img src="images/VBox51.PNG" width="400">
<br>

> 21. After restarting, you can immediately observe the changes in the screen. Also, you can now mount an USB drive.

> If you want to mount an USB drive, power off the VM and open the Settings.

<br>
<img src="images/VBox53.PNG" width="600">
<br>

> 22. Go to *Settings - USB*, press the right side icon, and find the device you want to mount.

<br>
<img src="images/VBox54.PNG" width="600">
<br>
<img src="images/VBox55.PNG" width="600">
<br>

> 23. Open the VM, and find the USB drive at *Devices - USB - NameoftheUSB*.

<br>
<img src="images/VBox56.PNG" width="600">
<br>

> 24. You can open the file manager and see the USB (in our case, appears as a "32 GB volume").

<br>
<img src="images/VBox57.PNG" width="600">
<br>

> 25. That's it. Now you have a fully functional **CentOS-Stream-8** VM in a **Windows 10** computer.

<br>
<img src="images/VBox52.PNG" width="800">
<br>

*Last updated: Antonio Mora, April 19th, 2021*
