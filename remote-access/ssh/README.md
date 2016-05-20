# SSH (Secure Shell)

You can remotely gain access to the command line of a Raspberry Pi from another computer on the same network using `ssh`.

Note you only have access to the command line, not the full desktop environment. For full remote desktop see [VNC](../vnc/README.md).

You can enable or disable the SSH server on your Raspberry Pi (it is enabled by default). This is done using [raspi-config](../../configuration/raspi-config.md):

Enter `sudo raspi-config` in the terminal, then navigate to `Advanced Options`, hit `Enter`, navigate to `SSH`, hit `Enter`, select one of the two options `<Enable>` or `<Disable>`, then press `Enter`. When you see a message stating 'SSH server enabled' or 'SSH server disabled', press `Enter` one more time (to accept the `<Ok>` option). You can then select `<Finish>` and press `Enter` to exit raspi-config.

SSH is built into Linux distributions and Mac OS, and a third-party SSH client is available for Windows. See the following guides for using SSH depending on the operating system used by the computer you are connecting from:

- [Linux & Mac OS](unix.md)
- [Windows](windows.md)
