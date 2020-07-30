# Connecting to stratus

## Connecting to the University of Minnesota (UMN) Virtual Private Network (VPN)

For security reasons, access to Stratus virtual machines is restricted to computers physically located on campus or connected to the campus network through a VPN.

Once a connection has been made to the UMN VPN, Stratus VMs can be accessed through Windows 10's built-in Remote Desktop Connection application.

---

### To connect to the UMN VPN with Cisco AnyConnect

Start Cisco AnyConnect and enter `nct.vpn.umn.edu` as the connection address and click `Connect`.

![anyconnect1](/images/anyconnect1.png)

A warning may pop up like the one below, select `Connect Anyway`.

![anyconnect2](/images/anyconnect2.png)

A login prompt will appear, for `Group:` select `AnyConnect-UofMSplit` and log in using your UMN username and password.

![anyconnect3](/images/anyconnect3.png)

If everything went smoothly you should see a globe icon with a padlock like the one below in your system tray.

![anyconnect4](/images/anyconnect4.png)

---

### To connect to your VM

Click start and begin to type `Remote Desktop...` until `Remote Desktop Connection` appears in the start menu. Click on `Remote Desktop Connection` to open the Windows Remote Desktop Connection application.

![rdp1](/images/rdp1.png)

Enter the ip address of your VM in the `Computer:` box. This should have been provided to you in an email.

![rdp2](/images/rdp2.png)

A warning may appear, select yes.

![rdp3](/images/rdp3.png)

A new screen with a blue background and a login box will appear. The blue bar at the top of the screen can be used to minimize, move, and close the remote desktop session. Enter `stateuser` and the password provided to you in an email into the login box and click `OK` to login.

![rdp4](/images/rdp4.png)

If the login was successful a dark blue desktop with the MDH logo will appear. **Congratulations!** You have successfully logged into your VM. 

![rdp5](/images/rdp5.png)
