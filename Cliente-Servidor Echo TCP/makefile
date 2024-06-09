all: server client

server:
	gcc echo-tcp-server.c -o echo-tcp-server.out

client: 
	gcc echo-tcp-client.c -o echo-tcp-client.out

clean:
	rm echo-tcp-server.out echo-tcp-client.out