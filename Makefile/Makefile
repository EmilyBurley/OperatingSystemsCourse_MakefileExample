CC	= gcc
CFLAGS	= -Wall
LDFLAGS	=
OBJFILES	= f1.o main.o
TARGET	= test

all: $(TARGET)

$(TARGET): $(OBJFILES)
	$(CC) $(CFLAGS) -o $(TARGET) $(OBJFILES) $(LDFLAGS)

clean:
	rm -f $(OBJFILES) $(TARGET) *~
