<p align="center">
<img src="https://i.imgur.com/chjNHqp.png" height="50%" width="50%" alt="ManageEngine ADManager Plus logo"/>
</p>

# Configuring ManageEngine ADManager Plus

This tutorial provides a comprehensive guide to configuring ManageEngine ADManager Plus, a powerful Active Directory management and reporting tool. Follow the steps below to ensure a successful configuration.

---

## Tools and Technologies Used

- **Platform**: Microsoft Azure (Virtual Machines/Compute)
- **Software**: ManageEngine ADManager Plus

---

## Operating Systems Used

- **Operating System**: Windows Server 2019/2022

---

## Overview of Steps

1. **Set Up the Environment**  
   - Deploy a virtual machine and install necessary dependencies.

2. **Install ManageEngine ADManager Plus**  
   - Download and install the software on your server.

3. **Configure Initial Settings**  
   - Set up user roles, permissions, and directory settings.

4. **Integrate with Active Directory**  
   - Connect ManageEngine ADManager Plus with your AD domain.

5. **Create and Assign Roles**  
   - Configure administrative roles and permissions.

6. **Test Configuration**  
   - Validate the setup and ensure proper functionality.

---

## Configuration Steps

### Step 1: Set Up the Environment

- **Action**: Deploy a virtual machine in Azure or a local server.  
  - Ensure the server meets the system requirements for ManageEngine ADManager Plus.
  - Install required dependencies such as Java and .NET Framework.

<p align="center">
<img src="" height="75%" width="100%" alt="VM setup"/>
</p>

---

### Step 2: Install ManageEngine ADManager Plus

- **Action**: Download the latest version of ManageEngine ADManager Plus from the official website.  
  - Run the installer and follow the prompts to complete the installation.

<p align="center">
<img src="" height="75%" width="100%" alt="Installing ADManager Plus"/>
</p>

---

### Step 3: Configure Initial Settings

- **Action**: Access the web interface and configure basic settings.  
  - Set up admin credentials and define the server URL.  
  - Enable HTTPS for secure communication.

<p align="center">
<img src="" height="75%" width="100%" alt="Initial settings configuration"/>
</p>

---

### Step 4: Integrate with Active Directory

- **Action**: Connect ManageEngine ADManager Plus to your Active Directory.  
  - Navigate to **Admin Settings > Domain Configuration** and add your domain details.  
  - Provide a domain admin account for authentication.

<p align="center">
<img src="" height="75%" width="100%" alt="AD integration"/>
</p>

---

### Step 5: Create and Assign Roles

- **Action**: Define roles and permissions for users.  
  - Navigate to **Admin Settings > Roles** and create roles such as Helpdesk Technician, Administrator, etc.  
  - Assign roles to users based on their responsibilities.

<p align="center">
<img src="" height="75%" width="100%" alt="Creating roles"/>
</p>

---

### Step 6: Test Configuration

- **Action**: Validate the setup by performing test operations.  
  - Check user account creation, password resets, and report generation.  
  - Ensure that permissions and roles are correctly applied.

<p align="center">
<img src="" height="75%" width="100%" alt="Testing configuration"/>
</p>

---

## Summary

This guide walked through the configuration of ManageEngine ADManager Plus, covering:  

- **Environment Setup**: Preparing the server.  
- **Software Installation**: Installing and accessing the application.  
- **Active Directory Integration**: Connecting to AD domains.  
- **Role Management**: Creating and assigning roles to users.  
- **Validation**: Ensuring the system operates as expected.  

With ManageEngine ADManager Plus configured, you can now efficiently manage Active Directory tasks, automate operations, and generate reports to streamline administrative workflows.
