main: main.o
	$(CC) main.o -o main

main.o:
	$(CC) -c main.c -Wall -Werror -fPIC

shared: main.o
	$(CC) -shared -o libmain.so main.o
