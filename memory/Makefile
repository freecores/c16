
all:	test

loader:	makemem.exe
	makemem ..\loader.bin

polled:	makemem.exe
	makemem ..\polled.bin

test:	makemem.exe
	makemem ..\test.bin

rtos:	makemem.exe
	makemem ..\rtos.bin

makemem.exe:	makemem.cc
	gcc -o $@ $<

clean:
	del makemem.exe
