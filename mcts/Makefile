.SILENT:

all:
	-mkdir build
	cd build; cmake ..; make
	ln -s build/mcts mcts

mcts: mcts.c
	gcc -g -Wall -DHAVE_ZLIB mcts.c -lz -o mcts

clean:
	-rm -r build mcts
