CC = gcc-14
CFLAGS = -std=c23

hello: hello.c
	$(CC) $(CFLAGS) hello.c -o hello

run: hello
	./hello

clean:
	rm -f hello output.txt