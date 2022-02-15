obj-m := helloworld.o

all: helloworld.c
	sudo make ARCH=arm CROSS_COMPILE=arm-linux-gnueabihf- -C ~/raspberrypi/linux M=$(PWD) modules


clean:
	sudo make ARCH=arm CROSS_COMPILE=arm-linux-gnueabihf- -C ~/raspberrypi/linux  M=$(PWD) clean


