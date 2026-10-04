Here is the **simple, fast GitHub `INSTRUCTIONS.md` format** for this troubleshooting lesson.

# vSphere Client Service Troubleshooting

## Problem

Error:

```text
vSphere Client service has stopped working
```

This usually means the **`vsphere-ui`** service has stopped or failed to start.

---

## Method 1 — Restart Using VAMI

1. Open a browser.
2. Go to:

```text
https://192.168.152.7:5480
```

3. Log in as **root**.
4. Open **Services**.
5. Find:

```text
VMware vSphere Client
vsphere-ui
```

6. Click **Start** or **Restart**.
7. Verify that the service is running.

---

## Method 2 — Restart Using SSH

1. Connect to the vCenter Server using **PuTTY** or another SSH client.

```text
192.168.152.7
```

2. Log in as **root**.
3. Enter:

```bash
shell
```

4. Check the service status:

```bash
service-control --status vsphere-ui
```

5. Restart the service:

```bash
service-control --restart vsphere-ui
```

6. Check the status again:

```bash
service-control --status vsphere-ui
```

---

## Verify

Confirm:

```text
vsphere-ui service    ✅ Running
vSphere Client        ✅ Accessible
```

**Status:** ✅ Troubleshooting Complete
