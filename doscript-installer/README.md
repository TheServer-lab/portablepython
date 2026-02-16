# DoScript Installer for PortablePython

This folder provides a simple **one-click Windows installer** for PortablePython using **DoScript**.

The goal of this script is to make the initial setup easier for beginners by automating the manual steps normally required after downloading PortablePython.

---

## What this installer does

The DoScript installer will:

1. Ask the user where to install PortablePython
2. Download the latest PortablePython archive
3. Extract the files automatically
4. Run `ensurepip` to enable **pip**
5. Verify that **Python** and **pip** are working correctly
6. Optionally help the user add Python to the system PATH
7. Show a clear success message when finished

This does **not** replace the normal installation method.
It is simply an **optional helper script** for users who prefer an automated setup.

---

## Requirements

* Windows operating system
* DoScript runtime installed
* Internet connection for downloading PortablePython

---

## How to use

1. Install or download DoScript.
2. Open a terminal in this folder.
3. Run:

```
doscript install.do
```

4. Follow the on-screen instructions.

After installation finishes, you should be able to run:

```
python --version
pip --version
```

---

## Why this exists

Setting up PortablePython on Windows currently involves several manual steps:

* Downloading and extracting archives
* Running commands to enable pip
* Configuring environment variables

This installer reduces the process to **a single guided script**, which may help:

* Beginners
* Students
* Quick testing environments

---

## Safety and scope

* This script **does not modify** the PortablePython project itself.
* It only automates steps a user would normally perform manually.
* Users can ignore this script and continue using the standard setup process.

---

## Feedback

Suggestions and improvements are welcome.
If maintainers prefer changes in structure, wording, or scope, the script can be easily adjusted.

Thank you for maintaining PortablePython and supporting beginner-friendly tooling.
