# VMware VM Setup Steps

## 1. Lab Prerequisites

- VMware Workstation
- Windows Server 2025 ISO
- Windows 11 ISO
  - These will be used to create the Domain Controller and (3) Windows Client VMs.

## 2. Create the Domain Controller VM

1. Open VMware Workstation on your host machine and select **Create a New Virtual Machine**.
2. Select **Typical** for the Virtual Machine Wizard.
3. Select the **Windows 2025 ISO** as the installer disc image file.
4. Configure the initial Windows installation information:
   - **Version of Windows:** Windows Server 2025 Datacenter
   - **VM Name:** Your Preferred Name (e.g. `DC01`)
   - **Full Name:** Your Preferred Name
   - **Password:** optional, but recommended
5. Click **Next**. It will warn that a product key was not entered. Select **Yes** to continue.
6. Select **Next** on the forward screens.
   - When you get to the screen that details the specs, I recommend customizing the memory and adjusting it to 4GB (4096 MB).
7. Click **Finish** to create the VM.

## 3. Create the Windows 11 Client VMs

> **Note:** Repeat this section 3 times to create `Client-1`, `Client-2`, and `Client-3`. Each VM needs a unique VM Name.

1. Same steps as **Creating the DC**, but this time make sure you select the **Windows 11 ISO**.
   - When prompted for the version of Windows, select **Windows 11 Pro**.
2. Complete the VM creation wizard as done previously.
