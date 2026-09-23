# VMware ESXi Hostname Configuration

## 01 - Objective

Change the default VMware ESXi hostname to a custom hostname and verify that the configuration is working correctly.

## 02 - Environment

 Personal Desktop  Laptop
 VMware Workstation Pro
 VMware ESXi
 ESXi Host Client

## 03 - Requirements

 VMware ESXi installed
 Access to ESXi Host Client
 Administrator access
 Network connectivity

## 04 - Configuration

1. Log in to the VMware ESXi Host Client.
2. Open Networking.
3. Navigate to the TCPIP or hostname settings.
4. Change the hostname.
5. Apply the configuration.
6. Verify the new hostname.

## 05 - Commands Used

```bash
hostname
esxcli system hostname get
```

## 06 - Testing

 Log out and back into the ESXi Host Client.
 Verify the hostname displayed in the interface.
 Run the hostname command from the ESXi shell.
 Confirm that the hostname resolves correctly on the network.

## 07 - Troubleshooting

### Issue

The new hostname did not appear immediately after the configuration.

### Solution

Restart the relevant network service or reboot the ESXi host when appropriate, then verify the hostname again.

## 08 - Results

The VMware ESXi host was successfully configured with the new hostname and the new configuration was verified.

## 09 - Lessons Learned

 Learned how to configure an ESXi hostname.
 Learned how to verify hostname settings.
 Practiced using ESXi command-line tools.
 Improved understanding of ESXi host administration.

## 📸 Screenshots

Screenshots for this lab are stored in the `screenshots` folder.
