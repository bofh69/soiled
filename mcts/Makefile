.SILENT:

all:
	test -d build || mkdir build
	cd build; cmake ..; make
	test -e mcts || ln -s build/mcts mcts

mcts: mcts.c
	gcc -g -Wall -DHAVE_ZLIB mcts.c -lz -o mcts

clean:
	-rm -r build mcts
