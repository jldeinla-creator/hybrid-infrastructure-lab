# VMware ESXi 6.5 — Quick Installation

## 1. Download ESXi

1. Go to the **Broadcom Support Portal**.
2. Sign in.
3. Open **VMware Cloud Foundation → Download**.
4. Search for **vSphere**.
5. Select **VMware vSphere Enterprise**.
6. Select **vSphere 8**.
7. Download the available **ESXi custom ISO**.

## 2. Create the ESXi Virtual Machine

1. Open **VMware Workstation**.
2. Click **Create a New Virtual Machine**.
3. Select **Install from ISO**.
4. Select the downloaded ESXi ISO.
5. Name the VM:

```text
ESXi-01
```

6. Set the virtual disk to approximately **80 GB**.
7. Select **Store virtual disk as a single file**.
8. Set memory to **4 GB**.
9. Set CPU to **2 processors/cores**.
10. Select **Power on this virtual machine after creation**.
11. Click **Finish**.

The ESXi installer should start automatically because the ISO is attached to the VM.

## 3. Install ESXi

When the ESXi installer starts:

1. Press **Enter**.
2. Press **F11** to accept the license.
3. Select the **80 GB virtual disk**.
4. Press **Enter**.
5. Select your **keyboard layout**.
6. Create the **root password**.
7. Press **F11** to confirm installation.
8. Wait for the installation to finish.

## 4. Reboot

1. When installation is complete, press **Enter**.
2. The ESXi server will reboot.
3. Allow ESXi to boot normally.

## 5. Release Mouse Cursor

To release the mouse from the VMware window:

```text
Ctrl + Alt
```

## 6. Verify

Confirm that:

* ESXi boots successfully.
* The ESXi server displays its startup screen.
* The virtual machine remains powered on.

**Status:** ✅ ESXi Installation Complete

