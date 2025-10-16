# 🐍 Password Manager - Day 29

[![Python Version](https://img.shields.io/badge/python-3.8%2B-blue.svg)](https://www.python.org/downloads/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/krishpatel-dev/Day29_password_manager/graphs/commit-activity)

Welcome to Day 5 of the Python learning journey! 🚀 This repository contains a secure and user-friendly Password Manager application built with Python and Tkinter. Store, generate, and manage your passwords with ease!

## 📋 Table of Contents
- [Features](#-features)
- [Getting Started](#-getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Usage](#usage)
- [How It Works](#-how-it-works)
- [File Structure](#-file-structure)
- [Contributing](#-contributing)

## ✨ Features

- 🔐 **Secure Password Storage**: Passwords are stored locally in a JSON file
- 🔄 **Password Generator**: Generate strong, random passwords with a single click
- 🔍 **Search Functionality**: Quickly find saved credentials by website name
- 📋 **Auto-copy**: Generated passwords are automatically copied to your clipboard
- 🎨 **User-friendly Interface**: Clean and intuitive GUI built with Tkinter
- 💾 **Persistent Storage**: Your data is saved between sessions

## 🚀 Getting Started

### Prerequisites
- Python 3.8 or higher
- Tkinter (usually comes with Python)
- pyperclip library

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/krishpatel-dev/Day29_password_manager.git
   cd Day29_password_manager
   ```

2. **Install required packages**
   ```bash
   pip install pyperclip
   ```

### Usage

Run the application:
```bash
python Proj29_password_manager.py
```

## 🛠 How It Works

### Adding a New Password
1. Enter the website name
2. Enter your email/username
3. Either type a password or click "Generate Password"
4. Click "Add" to save the credentials

### Finding a Password
1. Enter the website name in the website field
2. Click the "Search" button
3. Your saved credentials will be displayed in a popup

### Generating a Password
Click the "Generate Password" button to create a strong, random password that will be automatically copied to your clipboard.

## 📁 File Structure

```
Day29_password_manager/
├── Proj29_password_manager.py  # Main application code
├── data.json                  # Password storage
├── logo.png                   # Application logo
└── README.md                  # This file
```

## 🤝 Contributing

Contributions are welcome! Here's how you can contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

<div align="center">
  Made with ❤️ and ☕ by <b>Krish</b>
</div>
