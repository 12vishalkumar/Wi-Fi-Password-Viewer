# Wi-Fi Password Viewer

## Description
<p align="justify">✍This Python script retrieves and displays the saved Wi-Fi profiles and their corresponding passwords on a Windows machine. It utilizes the `subprocess` module to interact with Windows command-line tools.</p>

## Features
- List all saved Wi-Fi profiles on a Windows machine.
- Display the password for each Wi-Fi profile, if available.

## Requirements
- Python 3.x
- Windows Operating System

## Usage
Run the script in a command-line interface with administrator privileges to ensure it can access necessary system resources.

## How It Works
The script executes the `netsh wlan show profiles` command to list all Wi-Fi profiles and then retrieves the password for each profile using `netsh wlan show profile name="PROFILENAME" key=clear`.

## Disclaimer
This tool is intended for educational purposes and to assist users in managing their own network connections. Please use responsibly and legally.

## Version
1.0
