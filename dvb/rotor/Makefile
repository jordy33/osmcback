CC=gcc

SRC=rotor.c
OBJ=rotor.o

BIND=/usr/local/bin/

TARGET=rotor

CLIB=-lm
all: $(TARGET)

$(TARGET): $(OBJ)
	$(CC) $(CFLG) $(OBJ) -o $(TARGET) $(CLIB)

$(OBJ): $(HED)

install: all
	cp $(TARGET) $(BIND)

clean:
	rm -f $(OBJ) $(TARGET) *~

c.o: $(CC) -c $< -o $@
