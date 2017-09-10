#this is a makeile with two .c three .h
hello.out:hello.o Bmain.o Cmain.o
	gcc -o hello.out hello.o Bmain.o Cmain.o
hello.o:hello.c a.h
	gcc -c hello.c
Bmain.o:Bmain.c b.h
	gcc -c Bmain.c
Cmain.o:Cmain.c a.h b.h c.h
	gcc -c Cmain.c
clean:
	rm -f 2.o 3.o hello.o hello.out
