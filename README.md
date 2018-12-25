# character_device_driver
Character device driver with implementation of hashtable


Steps to build code -


1) sudo make
2) scp kprobe.ko hashtable ht530_drv.ko IP_OF_GALILEO:/home/root
3) insmod kprobe.ko
4) insmod ht530_drv.ko
5) ./hashtable
	a) It will ask for the offset of the write function where you want to add kprobe






