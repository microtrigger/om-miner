
CFLAGS += -Wall -g
AR := arm-linux-gnueabihf-ar

all: parsers.a

parsers.a: binary.o hex.o
	$(AR) rc $@ binary.o hex.o

clean:
	rm -f *.o parsers.a

.PHONY: all clean
