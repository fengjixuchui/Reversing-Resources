Dumping memory for VirtualBox (on OSX):
1. /Applications/VirtualBox.app/Contents/MacOS/VBoxManage list vms
2. /Applications/VirtualBox.app/Contents/MacOS/VBoxManage debugvm "Windows 10 x64" dumpvmcore --filename dump.elf
