

chip8-emulator: chip8.o main.o
	g++ chip8.o main.o -o chip8-emulator -lstdc++fs -lSDL2

chip8.o: chip8.cc
	g++ -c chip8.cc

main.o: main.cc
	g++ -c main.cc

clean:
	rm *.o
