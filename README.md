# Cursor

This guide explains how to install Cursor 0.48.8 on an AMD64 architecture running Ubuntu 24.04.

## Version Information

    Version: 0.48.8
    Architecture: AMD64
    Platform: Ubuntu 24.04
    Installation Package: Cursor_0.48.8_amd64.deb

## Installation Steps

### Download the `.deb` Installation Package

[Cursor_0.xx.x_amd64.deb](https://github.com/adysec/cursor/releases/latest)

### Install Cursor

Open a terminal and run the following command to install the `.deb` package

```bash
sudo dpkg -i Cursor_0.48.8_amd64.deb
```

### Launch Cursor

After installation, you can launch Cursor from the application menu or by running the following command in the terminal:

```bash
cursor
```

## New Features

The Cursor 0.48 update introduces the following key features:

    Chat Tabs: Support for multiple parallel conversations.

    Custom Modes (Beta): Allows you to create custom modes tailored to your workflow.

    Sound Notifications (Beta): Play a sound notification when a conversation is completed.

    Cost Visibility: View the cost breakdown for each chat based on usage.

For a detailed changelog, refer to the official release notes.

## Uninstall Cursor

If you wish to uninstall Cursor, run the following command:

```bash
sudo apt remove --purge cursor
```

## Support & Feedback

For more information or support, please visit the official Cursor website:

[https://www.cursor.com](https://www.cursor.com)

This README is designed to provide clear installation instructions for installing Cursor 0.48.8 on Ubuntu 24.04 without the need for additional dependencies.
