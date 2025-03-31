# 🌐 Soundness Testnet Key Generation Guide

## 🚀 Quick Start

### Step 1: Update and Install Required Packages

Before starting, make sure your system is up to date and the required dependencies are installed.

1.  Open a terminal and update your system packages by running the following commands:
    
    ```bash
    `sudo apt update && sudo apt upgrade -y
    sudo apt install -y pkg-config libssl-dev` 
    ```
    This will update your system and install essential libraries needed for Rust and other tools.
    

----------

### Step 2: Install Rust

Rust is the programming language used by many tools, including Soundness.

1.  Install Rust by running the following command:
    
    ```bash
    `curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs/ | sh` 
    ```
2.  When prompted, select the default installation (option 1). The installation may take a few minutes.
    
3.  Once installation is complete, activate Rust by running:
    
    ```bash
    `source  $HOME/.cargo/env` 
    ```
4.  To ensure that the environment is set up after rebooting, add the above command to your `.bashrc`:
    
    ```bash    
    `echo  'source $HOME/.cargo/env' >> ~/.bashrc source ~/.bashrc` 
    ```
----------

### Step 3: Install the Soundness CLI

To interact with Soundness, you need to install its command-line interface (CLI). Follow these steps:

1.  Install the Soundness CLI by running the following command:
    
    ```bash
    `curl -sSL https://raw.githubusercontent.com/soundnesslabs/soundness-layer/main/soundnessup/install | bash` 
    ```
    This will download and install the necessary components for working with Soundness.
    
2.  Once installed, activate the changes by running:
    
    ```bash
    `source ~/.bashrc` 
    ```
----------

### Step 4: Install and Update Soundness

After installing the CLI, you'll need to install and update the Soundness components:

1.  Install Soundness:
    
    ```bash
    `soundnessup install` 
    ```
2.  Update Soundness to the latest version:
    
    ```bash
    `soundnessup update` 
    ```

----------

### Step 5: Generate the Key for Registration

Now that everything is set up, you can generate the key for registration.

1.  Run the following command to generate the key:
    
    ```bash
    
    `soundness-cli generate-key --name "Your_Key_Name"` 
    ```
    Replace `"Your_Key_Name"` with a unique name for your key.
    
2.  After running the command, you'll receive your key, which can be used for testnet registration.
    

----------

## 🌟 Congratulations! 🎉

Your Soundness key is now generated and ready for registration on the testnet. 🚀
