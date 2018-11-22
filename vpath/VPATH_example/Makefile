# Comapre VPATH and GPATH

# GPATH = search_VPATH_directory
VPATH = search_VPATH_directory

# vpath %.c search_VPATH_directory

hello: hello.o
	cc -o hello hello.o

hello.o: hello.c
	cc -c $^

clean:
	rm hello *.o
