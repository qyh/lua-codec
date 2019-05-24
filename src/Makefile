all:
	gcc -Wall -O2 -shared -o codec.so codec.c -I /usr/include -lcrypto -fPIC -std=c99

clean:
	rm -f codec.so
