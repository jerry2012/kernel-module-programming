obj-m += preparedev.o
obj-m += preparedrv.o

all:
	#make -C /lib/modules/$(shell uname -r)/build  M=$(PWD) modules
	make ARCH=arm CROSS_COMPILE=/repo/ema/am57xx/ti-processor-sdk-linux-am57xx-evm-04.00.00.04/linux-devkit/sysroots/x86_64-arago-linux/usr/bin/arm-linux-gnueabihf- -C /repo/ema/am57xx/ti-processor-sdk-linux-am57xx-evm-04.00.00.04/board-support/linux-4.9.28+gitAUTOINC+eed43d1050-geed43d1050/ M=$(PWD)

clean: 
	#make -C /lib/modules/$(shell uname -r)/build  M=$(PWD) clean
	make ARCH=arm CROSS_COMPILE=/repo/ema/am57xx/ti-processor-sdk-linux-am57xx-evm-04.00.00.04/linux-devkit/sysroots/x86_64-arago-linux/usr/bin/arm-linux-gnueabihf- -C /repo/ema/am57xx/ti-processor-sdk-linux-am57xx-evm-04.00.00.04/board-support/linux-4.9.28+gitAUTOINC+eed43d1050-geed43d1050/ M=$(PWD) clean
