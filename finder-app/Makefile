CROSS_COMPILE=
CFLAGS=-Wall -Werror -pedantic -std=gnu99
CC=$(CROSS_COMPILE)gcc

writer: writer.c
	$(CC) $(CFLAGS) -o writer writer.c

clean:
	rm -f writer.o writer *~
