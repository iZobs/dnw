##Instruction
This app writen by `<hulifox008@163.com>`，i just find an copy in the internet and change
it to suit my TQ2440 arm9 board.

##Build:
You need libusb installed to build this tool. 
Please install libusb and libusb-dev before building.
To build this tool, just:
	
    gcc dnw2.c -o dnw2 -lusb

##Use:
Make sure you have `root privilege`. Use following 
command to download a file:

	./dnw2 <filename>

##BUG
Please feel free to report it to __ivincentlin@gmail.com__

