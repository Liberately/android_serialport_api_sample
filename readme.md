from https://code.google.com/archive/p/android-serialport-api/

archive [source-archive.zip](source-archive.zip)

```bash
emulator.exe -avd Pixel_3_API_28 -writable-system -qemu -serial COM2 -no-snapshot-load

adb root
adb shell setenforce 0 
adb shell chmod 666 /dev/ttyS1
```