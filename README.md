# Cloud-computing-lab
# Install a C Compiler in a Virtual Machine using VirtualBox and Execute a Simple Program

This project demonstrates how to install a C compiler inside a virtual machine (Ubuntu OS using VirtualBox), write a simple C program, compile it, and execute it successfully.

---

## Requirements

- Oracle VirtualBox
- Ubuntu ISO (download from [ubuntu.com](https://ubuntu.com/download))
- Internet connection inside VM
- Basic terminal knowledge

---

## Step 1: Set Up the Virtual Machine

1. Download and install [VirtualBox](https://www.virtualbox.org/)
2. Create a new virtual machine and load the Ubuntu ISO
3. Complete Ubuntu installation with default settings

*Screenshot: Ubuntu running inside VirtualBox*  
![Ubuntu VM](screenshots/ubuntu_vm.png)

---

## Step 2: Install the C Compiler (GCC)

Open a terminal in the virtual machine and run:

```bash
sudo apt update
sudo apt install build-essential -y
