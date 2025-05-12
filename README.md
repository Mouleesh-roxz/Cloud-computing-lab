# Cloud-computing-lab
Here's a sample `README.md` file for a GitHub repository that documents how to install a C compiler in a virtual machine using VirtualBox and execute a simple C program:

---

# 🖥️ C Compiler Setup in VirtualBox VM

This repository contains step-by-step instructions to install a C compiler in a virtual machine (VM) using **VirtualBox** and run a simple C program.

## 📋 Prerequisites

Before starting, ensure you have the following installed:

* [VirtualBox](https://www.virtualbox.org/)
* An ISO file for a Linux distribution (e.g., Ubuntu or Debian)
* At least 10 GB of free disk space
* Minimum 2 GB RAM for the VM

## 🚀 Steps to Setup

### 1. Create a New Virtual Machine

1. Open VirtualBox and click **New**.
2. Enter a name (e.g., `C_Compiler_VM`).
3. Choose **Linux** as the type and **Ubuntu (64-bit)** as the version.
4. Assign memory (RAM) – recommended: **2048 MB**.
5. Create a virtual hard disk – recommended: **10 GB (VDI)**.

### 2. Install the Operating System

1. Start the VM and select the downloaded **Linux ISO** when prompted.
2. Follow the on-screen instructions to install the OS.
3. Restart the VM after installation.

### 3. Install the C Compiler

Once inside the VM terminal, run the following commands:

```bash
sudo apt update
sudo apt install build-essential -y
```

> This installs the `gcc` compiler and other necessary build tools.

### 4. Write and Run a Simple C Program

1. Create a new C file:

```bash
nano hello.c
```

2. Paste the following code:

```c
#include <stdio.h>

int main() {
    printf("Hello, World!\n");
    return 0;
}
```

3. Save and compile:

```bash
gcc hello.c -o hello
```

4. Run the program:

```bash
./hello
```

### ✅ Output

You should see:

```
Hello, World!
```

## 📂 Repository Structure

```
.
├── README.md          # This file
└── hello.c            # Sample C program (optional)
```

## 🧠 Notes

* You can use any lightweight Linux distro like Lubuntu for faster performance in VM.
* Use `gedit`, `nano`, or `vim` as a text editor inside the VM.

## 📜 License

This project is licensed under the MIT License.

---

Would you like a `hello.c` file and a screenshot example added as well?
