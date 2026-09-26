## Frequently Asked Questions

### Where should I download Python?

Download Python from the [official Python website](https://www.python.org/downloads/). Avoid downloading it from unknown websites.

### Which version of Python should I install?

Install the latest stable version that supports your operating system. Check your project's requirements if you are installing Python for an existing project.

### What does “Add python.exe to PATH” mean?

PATH lets you run Python commands from a terminal. On Windows, select **Add python.exe to PATH** before starting the installation.

### How do I check whether Python is installed?

Open a terminal and run:

```bash
python --version
```

If that command does not work, try `python3 --version`. Windows users can also try `py --version`.

### Why does my computer say that Python is not found?

Python may not be installed, or its location may not be in PATH. Install Python again and select the PATH option on Windows. Then close and reopen the terminal before trying again.

### What is `pip`?

`pip` is Python's package installer. It lets you install additional Python libraries. For example:

```bash
python -m pip install requests
```

Use `python3` instead of `python` if that is the command used by your system.

### Do I need administrator permission?

You may need administrator permission to install Python for all users. If you do not have permission, ask your system administrator or choose an installation option for your user account when available.

### How do I know that Python works correctly?

Run this command:

```bash
python -c "print('Python is installed correctly.')"
```

If the message appears, Python can run a program successfully.
