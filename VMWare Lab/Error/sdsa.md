# vCenter Service Connection Recovery Guide

### Step 1: Connect via SSH
1. Open your terminal or SSH client (like **PuTTY**).
2. Connect to your vCenter Server IP or hostname.
3. Log in as **`root`** with your root password.

### Step 2: Run Recovery Commands
Copy and paste the commands below into your SSH terminal. 

```bash
# 1. Switch to the bash shell
shell

# 2. Check management service status
service-control --status applmgmt

# 3. Restart the management service
service-control --stop applmgmt && service-control --start applmgmt

# 4. IF STILL BROKEN: Force-start all vCenter core services
# (Note: This can take 5 to 10 minutes to finish)
service-control --start --all
```

### Step 3: Verify Access
* Wait **5 to 10 minutes** for all background processes to initialize.
* Open an incognito browser window and try logging into your **vCenter vSphere Client** or **VAMI (Port 5480)**.
