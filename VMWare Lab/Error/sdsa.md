# vCenter Server Appliance (VCSA) "Failed to Connect to Service" Recovery Guide

### Step 1: Connect to vCenter via SSH
1. Open your terminal or an SSH client (like **PuTTY**).
2. Connect to your vCenter Server IP address or hostname.
3. Log in using the username **`root`** and your root password.

### Step 2: Enable the Bash Shell
Once logged in, switch to the command-line shell:
1. Type **`shell`** and press **Enter**.
2. Your prompt will change, indicating you are now in the bash environment.

### Step 3: Restart the Management Service
The error is most commonly caused by a frozen or stopped Appliance Management Service (`applmgmt`). Run these commands to fix it:

* **To check if the service is running:**
```bash
service-control --status applmgmt
```

* **To restart the service (stops and starts it fresh):**
```bash
service-control --stop applmgmt && service-control --start applmgmt
```

### Step 4: Start All Services (If Step 3 Fails)
If restarting the management service does not fix the issue, other critical vCenter services might be stopped (often caused by full disk space or a sudden power outage).

* **To start all vCenter services at once:**
```bash
service-control --start --all
```
*(Note: This process can take 5 to 10 minutes to complete fully.)*
