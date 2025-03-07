# Tarinstall

A simple bash script to easily install Linux applications distributed as tar.gz files.

## Installation

1. Download the script:
```bash
curl -O https://raw.githubusercontent.com/yourusername/tarinstall/main/tarinstall
```

2. Make it executable:
```bash
chmod +x tarinstall
```

3. Move to system path:
```bash
sudo mv tarinstall /usr/local/bin/
```

## Usage

Basic usage:
```bash
tarinstall application.tar.gz
```

### Examples

Installing Visual Studio Code:
```bash
tarinstall code-stable-x64-linux.tar.gz
```

Installing Postman:
```bash
tarinstall Postman-linux-x64.tar.gz
```

## Features

- Automatically extracts tar.gz files to /opt
- Creates desktop shortcuts
- Adds program to system PATH
- Auto-detects executable files
- Searches for application icons
- Allows custom application names
- Removes previous installations

## Requirements

- Linux system
- sudo privileges
- tar command
- bash shell

## Notes

The script will:
1. Extract the contents to /opt/[appname]
2. Create a symlink in /usr/local/bin
3. Create a desktop entry
4. Make the application globally accessible

You can run the installed application by typing its name in the terminal or finding it in your applications menu.
