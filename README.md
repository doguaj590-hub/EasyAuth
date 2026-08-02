# EasyAuth

A simple and secure authentication system for your Minecraft server, designed for NeoForge 1.21.1.

## Features

This mod provides essential account security for players on your server:

/register <password> <confirm password> - Create a new account.
/login <password> - Log into your existing account.
/changepassword <new password> - Update your account password. Note: This command is only available after you have successfully authenticated (logged in).

## Installation

To use this mod, ensure you have the correct version of NeoForge installed.

1. Download NeoForge: Get the NeoForge 1.21.1 installer from the official website: https://neoforged.net/
2. Install NeoForge: Run the installer and follow the on-screen instructions to set it up for your Minecraft instance.
3. Download the Mod: Place the .jar file of this mod into your server's mods folder.
4. Launch: Start your server. The mod will automatically generate the necessary configuration files.

## Quick Start Guide

Follow these steps to secure your account upon joining:

1. Registration
If you are a new player, you must register first:
/register <password> <confirm password>

2. Login
Upon subsequent joins, authenticate using your password:
/login <password>

3. Change Password
If you need to update your credentials, ensure you are logged in first, then use:
/changepassword <new password>

Security Tip: Always use a unique password that you do not use on other platforms.
