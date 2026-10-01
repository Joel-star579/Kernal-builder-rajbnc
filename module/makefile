obj-m += module.o

all:
	make -C ../kernel_src M=$(PWD) ARCH=arm64 CROSS_COMPILE=aarch64-linux-gnu- modules

clean:
	make -C ../kernel_src M=$(PWD) ARCH=arm64 CROSS_COMPILE=aarch64-linux-gnu- clean

