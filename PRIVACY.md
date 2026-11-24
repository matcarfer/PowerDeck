# Privacy policy

[Español](PRIVACY.es.md) · **English**

*Last updated: 2026-11-11 · Applies to PowerDeck (`io.github.matcarfer.powerdeck`), all versions.*

**PowerDeck does not collect, share or sell any data. Nothing leaves your device.**

- **No internet permission.** No servers, accounts, ads, analytics or trackers; no third-party libraries. The only permissions are `ACCESS_NETWORK_STATE` (to show this device's IP) and, optionally, `WRITE_SECURE_SETTINGS`, which only you can grant from a computer, to switch adb without root.
- It only runs, on the device itself, the action you confirm (power off, reboot, adb switches…): through `su` with root, or by changing the adb settings without root.
- **Stored on the device:** nothing personal. The adb switches leave a boot script in `/data/adb/service.d` and two system properties (`debug.powerdeck.*`) only while you keep them on; turning them off removes them.
- If this policy ever changes, the change will be listed in the [CHANGELOG](CHANGELOG.md). Questions: open an issue.
