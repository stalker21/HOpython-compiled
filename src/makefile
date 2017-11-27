CC=gcc
CFLAGS=-Wall -ggdb -fPIC
LDFLAGS=-fPIC -shared

milibreria.so: add_two.o arrays.o
	$(CC) $(LDFLAGS) -o $@ $^ 
