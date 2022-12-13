obj-m += minifw.o

all:
	#make -C /usr/src/kernels/$(shell uname -r)/build M=$(PWD) modules
	make -C /lib/modules/$(shell uname -r)/build M=$(PWD) modules
clean:
	#make -C /usr/src/kernels/$(shell uname -r)/build M=$(PWD) clean
	make -C /lib/modules/$(shell uname -r)/build M=$(PWD) clean
