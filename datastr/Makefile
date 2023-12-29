SRC:= $(wildcard *.c)
OBJ:= $(SRC:.c=.o)

build: $(OBJ)
	gcc -Wall -g -o test $(OBJ)

%.o: %.c
	gcc -Wall -g -c -o $@ $<

clean:
	rm *.o test
