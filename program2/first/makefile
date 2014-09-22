prog: prog1.o prog2.o
	gcc prog1.o prog2.o -o prog

prog1.o: prog1.c
	gcc -c prog1.c

prog2.o: prog2.c
	gcc -c prog2.c

clean:
	rm *.o prog

archive: 
