CC=g++
CFLAGS = -Wall -Werror -pedantic
LFLAGS = -lsfml-graphics -lsfml-system -lsfml-window -lsfml-audio

all: run_game	

run_game: main.o 
	$(CC) $(CFLAGS) main.o -o run_game $(LFLAGS)

main.o: main.cpp 
	$(CC) main.cpp -c

clean:
	rm -f *.o run_game 