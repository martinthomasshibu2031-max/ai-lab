## Installing Python

Follow these steps to install Python on your computer.

### Software Requirements

You need:

- A computer running Windows, macOS, or Linux
- An internet connection
- Permission to install software on the computer
- Enough free storage for Python and its tools

### Installation Steps

#### Windows

1. Open the [official Python website](https://www.python.org/downloads/).
2. Download the latest stable Windows installer.
3. Open the downloaded installer.
4. Select **Add python.exe to PATH**.
5. Select **Install Now**.
6. Wait for the installation to finish, then close the installer.

#### macOS

1. Open the [official Python website](https://www.python.org/downloads/).
2. Download the latest stable macOS installer.
3. Open the downloaded installer package.
4. Follow the instructions on the screen.
5. Enter your computer password if prompted.
6. Close the installer when the installation is complete.

#### Linux

1. Open a terminal.
2. Use your distribution's package manager to install Python. For example, on Ubuntu or another Debian-based system, run:

	```bash
	sudo apt update
	sudo apt install python3 python3-pip
	```

3. Enter your password if prompted.
4. Wait for the installation to finish.

### Verification Steps

1. Open Command Prompt or PowerShell on Windows, or a terminal on macOS or Linux.
2. Check the installed Python version:

	```bash
	python --version
	```

	On some systems, use `python3 --version` instead. Windows users can also use `py --version`.

3. Confirm that Python can run a program:

	```bash
	python -c "print('Python is installed correctly.')"
	```

	If your system uses `python3`, replace `python` with `python3`.

If the command displays a Python version and the message appears, Python is installed and ready to use.
