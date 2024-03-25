# Ansible Project - Copy and Execute Script

## Introduction

This project aims to automate the process of copying and executing a shell script (`fs_status.sh`) on remote hosts using Ansible. The script performs file system status checks and provides relevant information.

## Technology Used

- Ansible

## Features

- Copying the `fs_status.sh` script to managed hosts.
- Executing the `fs_status.sh` script on the managed hosts.
- Restarting the Postfix service on the web servers.

## Usage

To use this project, follow these steps:

1. Clone the repository.
2. Ensure Ansible is installed on your system.
3. Update the `ansible.cfg` file as needed.
4. Update the `inventory` file with the IP addresses of your managed hosts.
5. Ensure `fs_status.sh` script is available at the specified source path.
6. Run the `script.yml` playbook using the command:
