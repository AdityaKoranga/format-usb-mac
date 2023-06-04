# format-usb-mac
erasing/mounting error in macos

First find the usb using the command:
```bash
diskutil list
```

> it will be disk 4 probably most of the time

now erase it:
```bash
diskutil eraseDisk free EMPTY /dev/disk4
```

It is erased successfully.
