C_FLAGS	= -Wall -pedantic -ansi -g -O2 -std=c++11
L_FLAGS	= 

O_FILES	= socket.o server.o main.o

all:	$(O_FILES)
	rm -f SocketMud
	c++ -o SocketMud $(O_FILES) $(L_FLAGS)

$(O_FILES): %.o: %.cpp
	c++ -c $(C_FLAGS) $<

clean:
	rm -f *.o
	rm -f SocketMud
