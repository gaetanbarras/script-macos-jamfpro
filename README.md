# 🚀 macOS Scripts for Jamf Pro

This repository contains a curated collection of **macOS management scripts** used with **Jamf Pro**.  
They automate common administrative tasks for macOS devices — account management, software deployment, pop-up notifications, and system maintenance.

---

## 🧩 Overview

Each script is a `.txt` file containing **ready-to-use shell or AppleScript code**.  
They are organized by function and can be copied directly into **Jamf Pro policies**, **Self Service**, or **Extension Attributes**.

---

## 🧑‍💻 Categories

### 👥 Account & Permissions
Scripts related to user account management and privilege changes.

| Script | Description |
|--------|--------------|
| `Change Account Type to Standart.txt` | Converts an admin account to a standard user. |
| `User standart to admin.txt` | Promotes a standard user to admin. |
| `Hidden Admin account.txt` | Creates a hidden administrator account. |
| `Create Exa User.txt` | Creates a specific user account automatically. |
| `Clean Account Data.txt` | Removes user folders or resets account data. |

---

### 🌐 Network & Connectivity
Tools for managing Wi-Fi, VPNs, and Kerberos.

| Script | Description |
|--------|--------------|
| `Disable WIFI.txt` | Disables Wi-Fi interfaces. |
| `Remove VPN New Version.txt` | Cleans up older VPN configurations. |
| `Remove School Connection.txt` | Removes predefined network connections. |
| `Cups Kerberos enable 02-2019.txt` | Enables Kerberos authentication for printing. |

---

### ⚙️ System & Maintenance
Scripts for macOS cleanup, restart prompts, and configuration resets.

| Script | Description |
|--------|--------------|
| `Erase OSX.txt` | Factory resets macOS (older versions). |
| `Erase OSX BigSur.txt` | Erases macOS Big Sur and later versions. |
| `Restart Pop Up.txt` | Displays a popup asking the user to restart. |
| `Script Flush DNS.txt` | Flushes the DNS cache. |
| `Remove App.txt` | Removes an application by name or path. |
| `Rename Computer.txt` | Renames the Mac using naming conventions or serial number. |

---

### 🧭 Applications & Configuration
Automates app installation, removal, and settings.

| Script | Description |
|--------|--------------|
| `Google Chrome Install.txt` | Installs or updates Google Chrome. |
| `Change HomePage Safari - Chrome.txt` | Sets a custom homepage for browsers. |
| `Default Browser.txt` | Forces a default browser. |
| `Uninstall chrome token.txt` | Removes Chrome authentication tokens. |
| `Uninstall Privileges.txt` | Uninstalls Privileges.app. |

---

### 🔒 Security & MDM
MDM management and privilege monitoring.

| Script | Description |
|--------|--------------|
| `Trust JAMF MDM Profile.txt` | Re-trusts the Jamf MDM profile on the Mac. |
| `launchPrivilegesAudit.txt` | Audits user privileges and logs results. |
| `Deledao Hidden App.txt` | Hides or removes Deledao filtering software. |

---

### 💬 Notifications & Pop-ups
Creates informative pop-ups and reminders via `swiftDialog` or `osascript`.

| Script | Description |
|--------|--------------|
| `pop up for request update.txt` | Prompts the user to update macOS. |
| `pop up not last version mac os.txt` | Warns if the system is outdated. |
| `pop up restart.txt` | Requests a restart with visual feedback. |
| `Restart Pop Up Printer.txt` | Notifies about printer restart or setup. |

---

### 🧰 Utilities & Miscellaneous
Handy tools for UI customization, hardware toggling, and remote control.

| Script | Description |
|--------|--------------|
| `Dock Empty.txt` | Clears all Dock items. |
| `Bluetooth ON.txt` | Ensures Bluetooth is enabled. |
| `Rustdesk Configuration.txt` | Configures Rustdesk for remote access. |
| `Screen Recording Information.txt` | Displays screen recording permission info. |

---

## 🧑‍💼 Usage with Jamf Pro

Each `.txt` file can be:

1. Copied into a **Jamf Pro Policy > Scripts** section.
2. Executed via **Self Service** for on-demand actions.
3. Used as part of **enrollment workflows** or **maintenance tasks**.
4. Adapted into **Extension Attributes** for reporting custom data.

Example command to test a script locally:
```bash
sudo bash "Change Account Type to Standart.txt"
```

---

## 🧾 License

This project is licensed under the **MIT License**.

```
MIT License

Copyright (c) 2025

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

[...]
```

---

## 👨‍💻 Author

**Gaëtan Barras**  
💼 Scripts designed for use in professional Jamf Pro environments.
