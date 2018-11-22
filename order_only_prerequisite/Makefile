hello: hello.o
	cc -o hello hello.o

hello.o: hello.c | testdir
	cc -c hello.c

testdir:
	mkdir testdir

clean:
	rm hello *.o
