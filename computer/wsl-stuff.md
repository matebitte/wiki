
# WSL Notes
## Auto-Startup


## Mount external Storage
[Original Article](https://www.scivision.dev/mount-usb-drives-windows-subsystem-for-linux/)
replace "f" with the respective drive letter:

```shell
mkdir /mnt/f

mount -t drvfs f: /mnt/f
```

