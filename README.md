# Remote Access Guide
## Contents
* [Setting Up The University VPN](#setting-up-the-university-vpn)
* [Remotely Accessing A Windows Machine](#remotely-accessing-a-windows-machine)

## Setting Up The University VPN
The university supplies a VPN solution for accessing the internal network from external sources (E.g. Your home!)

1. Go to http://remote.lincoln.ac.uk/

    ![](images/landing.png)

2. Enter your University username and password (e.g. your student account or staff account)

3. Click "continue"

4. On the left-hand side, click "VPN Client (Any Connect)"

    ![](images/anyconnect_link.png)

5. Click "start AnyConnect"

    ![](images/click_start.png)

6. Click the Download button

    ![](images/download.png)

7. Run the installer
    - Click "Next"
    - Select "I accept the terms in the license agreement" and click "Next"
    - Click "Install"
    - Wait for the install to finish
    - Click "Finish"

8. Open Cisco AnyConnect on your machine
    - You may be required to enter remote.lincoln.ac.uk as your connection target. (Windows should configure this automatically)
    - Click "Connect"

    ![](images/anyconnect_open.png)

9. Enter your University login details in the now open open window

    ![](images/anyconnect_login.png)

10. Click "Accept" on the new prompt

11. You should now be connected to the University supplied VPN and will be able to access the internal network

12. The status of your connection to the VPN is visible via the icon in your Operating System's system tray

    ![](images/system_tray_icon.png)


## Remotely Accessing A Windows Machine
Feel free to setup the VNC viewer/client of your choice, but the following guide will be using RealVNC's remote client.

1. Go to https://www.realvnc.com/en/connect/download/viewer/

2. Choose your operating system.

    ![](images/realvnc_os.png)

3. Click the "Download VNC Viewer".

    ![](images/download_realvnc_button.png)

4. Run the downloaded installer and follow these steps:
    - Select your language of choice
    - Click "Next"
    - Click "I accept the terms in the License Agreement"
    - Click "Next"
    - Change the install location if needed
    - Click "Next"
    - Click "Install"
    - Click "Finish"

5. Open the "VNC Viewer" application which has been installed.

    ![](images/realvnc_client.png)

6. Ensure you are on the University supplied VPN (make sure AnyConnect is running and connected), see the above guide if setup is required.

    ![](images/system_tray_icon.png)

7. On the VNC Viewer application, enter your assigned IP address in the "Enter a VNC Server addess or search" box. You may be required to append port 5900 to your assigned ip address, for example: 192.168.0.1:5900.

    ![](images/realvnc_ip_box.png)

    ![](images/realvnc_ip_enterred.png)

8. Press Enter to launch the connection and click "Continue" on "Unencrypted connection" prompt which will open.

9. Enter your assigned password in the login prompt.

    ![](images/realvnc_login.png)

10. Press Enter and you should now be connected to the desktop

    ![](images/connected_desktop.png)

