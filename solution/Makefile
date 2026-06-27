CFLAGS = -Wall -Wextra

.PHONY: all check test clean

all: helloworld

check:
	cpplint helloworld.c

test: helloworld
	./test.sh

helloworld: helloworld.c

clean:
	-rm -f helloworld
	-rm -f *~
