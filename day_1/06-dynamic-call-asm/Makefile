program: program.c lib.a
	gcc -L . -o program program.c -llib -O0 -s

lib.a: lib.c
	gcc -c -fPIC lib.c -o lib.o
	gcc -shared -o liblib.so lib.o
