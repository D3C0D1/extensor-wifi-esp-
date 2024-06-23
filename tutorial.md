pip3 install esptool --break-system-packages

sudo chmod a+rw /dev/ttyUSB0

esptool.py -p /dev/ttyUSB0 write_flash -fm dout 0x0000 0x00000.bin 0x02000 0x02000.bin


intruccion

submask 192.168.4.1
