# DNS Switcher & IP Blocker

![Tauri](https://img.shields.io/badge/Tauri-v2-blue?style=for-the-badge&logo=tauri)
![Rust](https://img.shields.io/badge/Rust-latest-orange?style=for-the-badge&logo=rust)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6%2B-yellow?style=for-the-badge&logo=javascript)
![License](https://img.shields.io/badge/License-CC%20BY--ND%204.0-lightgrey?style=for-the-badge)

## Project Description

**DNS Switcher & IP Blocker** is a powerful network management tool developed as a cross-platform desktop application using the Tauri framework. It provides users with a convenient way to switch DNS servers and block unwanted IP addresses, enhancing security and control over network traffic.

**Note:** This project is currently in active development, and the current version is not final. It has been primarily tested on **Windows 11**.

## Key Features

*   **DNS Server Switching**: Easily switch between predefined lists of DNS servers (OpenDNS, Google DNS, Cloudflare, Quad9, etc.) or use your own custom ones.
*   **Special DNS**: Automatic detection and saving of current system DNS settings upon first activation, with an option for manual input.
*   **IP Blocking**: Block access to websites by categories (e.g., games, adult content).
*   **Import/Export Settings**: Save and load application configurations for backup or transfer to other devices.
*   **Multi-language Interface**: Support for multiple languages for user convenience.
*   **User-Friendly Interface**: An intuitive user interface for easy management of network settings.

## Technologies Used

*   **Tauri v2**: A cross-platform framework for building desktop applications using web technologies.
*   **Rust**: The application's backend, ensuring high performance and security.
*   **JavaScript (Vanilla JS)**: The application's frontend, responsible for the user interface.
*   **HTML/CSS**: Interface structure and styling.

## Configuration

Key configuration files:

*   `storage.json`: The file where user application settings are stored (language, active interface, blocked IPs, etc.).