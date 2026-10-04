Here is the **simple, fast GitHub `INSTRUCTIONS.md` version** for your vCenter installation lab.

# vCenter Server Appliance — Quick Installation

## 1. Check ESXi Resources

Verify the target ESXi host has enough resources.

```text
ESXi2 RAM:     12 GB
CPU:           2
Disk Space:    300 GB
```

## 2. Download VCSA

1. Download the **vCenter Server Appliance (VCSA) ISO**.
2. Mount the ISO.
3. Open the VCSA files.

## 3. Choose Installation Method

There are two ways to install vCenter:

### Method 1 — Deploy OVA

```text
ESXi Host Client
→ Create/Register VM
→ Deploy a virtual machine from an OVF or OVA file
→ Select OVA
→ Select Datastore
→ Select Network
→ Select Deployment Size
→ Configure Settings
→ Finish
```

### Method 2 — VCSA GUI Installer

```text
Mount ISO
→ vCenter Server Appliance
→ vcsa-ui-installer
→ Install
```

For this lab, use **Method 2**.

## 4. Stage 1 — Deploy vCenter

1. Select **Install**.
2. Enter the vCenter deployment details.
3. Select **Embedded Platform Services Controller**.
4. Select **Tiny** deployment size.
5. Target ESXi:

```text
ESXi2
192.168.19.6
```

6. Authenticate using the **ESXi root account**.
7. Configure the vCenter network:

```text
IP Address:    192.168.19.7
Subnet Mask:   255.255.255.0
Gateway:       192.168.19.2
DNS:           192.168.19.2
```

8. Use the **IP address as the system name** because the lab does not have a DNS server.
9. Enable **Thin Disk Mode**.
10. Review the settings.
11. Click **Finish**.

Stage 1 will deploy the vCenter Server Appliance to ESXi2.

## 5. Stage 2 — Configure vCenter

After Stage 1 completes:

1. Continue to **Stage 2**.
2. Complete the vCenter configuration.
3. Apply the required settings.
4. Finish the configuration.

## 6. Verify

Confirm:

```text
VCSA deployed       ✅
Stage 1 completed   ✅
Stage 2 completed   ✅
vCenter IP:         192.168.19.7
Target ESXi:        ESXi2
Deployment:         Tiny
PSC:                Embedded
Disk Mode:          Thin
```

**Status:** ✅ vCenter Server Appliance Installed
