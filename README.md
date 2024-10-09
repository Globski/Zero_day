# Zero Day - Setting Up Your Local Coding Environment

[![Linux](https://img.shields.io/badge/OS-Ubuntu-green)](https://ubuntu.com/)

## Description

This project focuses on setting up your local coding environment for development using tools like Vagrant and Docker in an Ubuntu environment. By the end of this project, you will have a fully functional local environment that mirrors the Ubuntu system, allowing you to work efficiently and without internet access.

## Project Structure

| Task                              | Description                                                                                          | Source Code                  |
|-----------------------------------|------------------------------------------------------------------------------------------------------|-------------------------------|
| 0. Create and setup your Git and GitHub account | Set up your Git and GitHub account and create your first repository.                     | [0-create_git_account.md](0-create_git_account.md)       |
| 1. Hello Ubuntu                   | SSH into your Ubuntu VM and document the output of the `uname` command.                          | [1-hello_ubuntu.md](1-hello_ubuntu.md)       |

## Environment
- All files will be executed on Ubuntu 20.04 LTS using Vagrant or Docker.

## Requirements

- All your files should end with a new line.

## Learning Objectives

At the end of this project, you should be able to:

- Explain what a virtual machine is and its benefits.
- Describe Vagrant and its usage in development.
- Identify the creator of Vagrant.
- Explain what Ubuntu is and its significance in the development world.
- Understand the meaning of “Ubuntu.”
- Utilize VMs with Vagrant effectively.
- Explain the functionality of the `uname` command.

## How to Use

1. Set up your Git and GitHub account following the instructions provided in the tasks.
2. Clone the repository and navigate to the project directory.
3. Follow the instructions in the tasks to complete the project.

### Setup Instructions

1. **Install Git**:
   ```bash
   sudo apt-get update
   sudo apt-get upgrade
   sudo apt-get install git
   ```

2. **Create a Repository**:
   - Go to GitHub and create a new repository named `zero_day`.
   - Clone the repository to your local machine:
     ```bash
     git clone <repo-url>
     ```

3. **Initialize Your Project**:
   - Navigate to the `zero_day` directory and create a subdirectory named `0x00-vagrant`.
   - Add a `README.md` file to the `0x00-vagrant` directory to describe the project.

4. **Use Vagrant**:
   - Install Vagrant and VirtualBox (or your preferred VM provider).
   - Create a `Vagrantfile` in the `0x00-vagrant` directory to configure your VM.

## Additional Notes

- **Virtual Machine**: A virtual machine (VM) is an emulation of a computer system that allows you to run multiple operating systems on a single physical machine.
- **Vagrant**: Vagrant is a tool that helps you manage and configure VMs easily, making it simple to create and share development environments.
- **Ubuntu**: Ubuntu is a popular Linux distribution that provides a user-friendly interface and is widely used in development and server environments.

This project serves as a fundamental step in your journey to becoming a proficient developer. By setting up your own local coding environment, you’ll gain valuable skills that will be essential for future projects. Happy coding!
