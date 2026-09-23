# ESXi Management Network — Quick Instructions

## 1. Configure Static IP

Assign a **static IP address** to the ESXi server so the IP remains consistent throughout the lab.

> The lecture recommends using a static IP so you can easily remember and access the ESXi server.

## 2. Test Management Network

1. Open the ESXi **Direct Console User Interface (DCUI)**.
2. Go to **Test Management Network**.
3. Run the network test.
4. Verify that the following are reachable:

   * Gateway
   * DNS

If the test succeeds, the network configuration is working.

## 3. Other Configuration Options

The ESXi configuration menu also provides:

* **Network Restore** — restore network settings.
* **Configure Keyboard** — change keyboard layout.
* **Troubleshooting Options** — troubleshoot ESXi.
* **View System Logs** — view system logs.
* **View Support Information** — view support information.
* **Reset System Configuration** — reset configuration to defaults.

## 4. Verify

Confirm:

```text
Static IP configured    ✅
Gateway reachable       ✅
DNS reachable           ✅
Management network      ✅
```

**Status:** ✅ Management Network Configured

## 5. Next Step

The next lab is to access the **ESXi server through the vSphere Web Client** and begin creating virtual machines.
