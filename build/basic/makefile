SRC := \
../../src/ \

BLD := \
./

OBJS := \
*.o

basic.clean:
	rm -f $(OBJS)
	
basic.compile:
	gcc ../../src/basic.c -o $(BLD)basic.o

basic.run:
	$(BLD)basic.o
	
basic.all: basic.clean basic.compile basic.run