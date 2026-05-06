# 🛠️ ssh-api - Simple control for your remote servers

[![](https://img.shields.io/badge/Download-Latest_Release-blue.svg)](https://github.com/jhosuemiscanvilchez/ssh-api/releases)

ssh-api gives you a bridge between your computer and your Linux servers. You manage files, run system commands, and handle server tasks through a simple interface. This tool removes the need for complex command-line knowledge. It automates Linux administration tasks while keeping your workflow organized.

## 📥 Getting the software

You need to download the installer from the release page. 

[Download the latest version here](https://github.com/jhosuemiscanvilchez/ssh-api/releases)

Follow these steps:

1. Click the link above.
2. Look for the section labeled "Assets".
3. Select the file ending in `.exe` for Windows.
4. Save the file to your "Downloads" folder.

## ⚙️ Setting up your system

The application works on Windows 10 and Windows 11. Your computer needs at least 4GB of RAM and a stable internet connection to communicate with your remote servers. Ensure you have network access to the servers you plan to manage.

1. Open your "Downloads" folder.
2. Double-click the `ssh-api.exe` file.
3. Windows might show a security prompt. Click "More info" and then "Run anyway" if the system asks.
4. Follow the instructions on the screen to complete the installation.
5. Create a desktop shortcut when the installer asks.

## 🚀 Running the application

Double-click the ssh-api icon on your desktop to start the program. The application boots and opens a small window that acts as your command center. You see a dashboard where you add your server details.

To connect your first server:

1. Click the "Add Server" button.
2. Type the IP address of your Linux server.
3. Enter your server username.
4. Provide your password or select your private key file.
5. Click "Save Connection".

The system tests the connection. A green indicator shows that the server is ready for your commands.

## 📋 Managing your servers

The dashboard categorizes your operations. You select a server from the list on the left to see available tools.

### Executing commands
You type your Linux commands in the text box. The software sends these to the server and prints the result in the window below. This helps you check system status or update server software without using an external terminal.

### File transfers
You move files between your Windows PC and your Linux server using the "File Transfer" tab. Drag files from your computer into the window to copy them to the server. You drag files from the server window back to your PC to download them. 

### Automating tasks
Store common tasks as "Quick Scripts." If you run the same update sequence daily, save those commands in this tab. Click the "Run" button to execute the full sequence. The application handles the timing and reports if the task finished with success.

### Tunnels
Create secure tunnels to bypass network restrictions. Enter the port numbers you need to map. The system keeps the tunnel active until you click "Stop". This feature links your local web browser to services running on your remote Linux server.

## 🛡️ Best practices for security

Keep your access credentials safe. Do not share your private key files. Store them in a folder that requires a password to open. Use strong passwords for your server accounts. 

Check for updates every few weeks. The application notifies you when a new version exists. Download the new version from the link provided earlier to keep your system patched against risks.

## 💡 Troubleshooting common issues

If you encounter problems, check these items:

* **Connection Timeout:** Check if your server is online. Ensure your internet connection is active. 
* **Permission Denied:** Verify your username and password. Ensure the user account on the server has the required permissions to perform the task.
* **Firewall Blocks:** Your local network might block the connection. Ensure your router allows traffic on the SSH port, usually port 22.
* **File Not Found:** Double-check the file path in the "File Transfer" section. Use the "Browse" button to locate files on your computer. 

If the application hangs or crashes, restart the process from your task manager. Close the window and launch it again to clear temporary glitches. Reach out to the support channels listed on the repository page if the issue persists after a restart.