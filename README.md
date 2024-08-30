# Keylogger
This repository contains an educational project demonstrating a Python-based keylogger that utilizes the Fernet symmetric encryption algorithm to secure captured data.
Keystroke Logging: The keylogger captures and records all keystrokes.
Active Window Logging: Along with keystrokes, the keylogger also records the active window title, providing context to the captured keystrokes.
Timestamp: Each recorded keystroke is accompanied by a timestamp, providing a chronological context to the logged data.
Fernet Encryption: All captured data is encrypted using the Fernet symmetric encryption algorithm, ensuring the security of the logged data.
Educational Purpose
This project is created purely for educational purposes. It serves as a practical example to understand the workings of keyloggers, the application of encryption techniques, and the importance of data security.


## Overview

This project is a simple keylogger implemented in Python. A keylogger is a tool that records keystrokes made on a keyboard. This particular implementation is designed for educational purposes to demonstrate how keystrokes can be captured programmatically.

**Important:** Using or distributing keyloggers without consent is illegal and unethical. Always obtain explicit permission before monitoring any system.

## Features

- Captures keystrokes in real-time.
- Logs keystrokes to a local file.
- Configurable settings for logging behavior.

## Prerequisites

- Python 3.x
- `pynput` library (for capturing keyboard events)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/keylogger-project.git
    cd keylogger-project
    ```

2. Install the required Python package:
    ```bash
    pip install pynput
    ```

## Usage

1. Navigate to the project directory:
    ```bash
    cd keylogger-project
    ```

2. Run the keylogger script:
    ```bash
    python keylogger.py
    ```

3. The keylogger will start capturing keystrokes and logging them to `keylog.txt` in the same directory.

## Configuration

You can adjust the logging behavior by modifying the `keylogger.py` script. Look for configuration options in the script to:

- Change the log file name.
- Adjust the logging interval or other parameters.

## Contributing
If you want to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (git checkout -b feature-branch).
3. Make your changes.
4. Commit your changes (git commit -am 'Add new feature').
5. Push to the branch (git push origin feature-branch).
6. Create a new Pull Request.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

## Disclaimer
This project is provided for educational purposes only. Use it responsibly and ensure you have permission to log keystrokes on any system you test it on. Misuse of this tool may result in legal consequences.
