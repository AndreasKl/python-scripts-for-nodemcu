## Commands

### Flash

```./esptool.py --port /dev/tty.SLAB_USBtoUART erase_flash```

```./esptool.py --port /dev/tty.SLAB_USBtoUART write_flash -fm dio 0x00000 /Users/buttercup/Downloads/esp8266-20161110-v1.8.6.bin```

### Connect

```screen /dev/tty.SLAB_USBtoUART 115200```

Exit screen with `CTRL+A` und `CTRL+D`

```screen -r```

### Upload a user script
