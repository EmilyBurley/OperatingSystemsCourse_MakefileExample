# Set the C compiler to gcc.
CC	= gcc

# For the C flags, choose the -Wall option, which enables most warning messages to help catch potential issues in the code.
CFLAGS	= -Wall

# Set no linker flags.
LDFLAGS	=

OBJFILES	= f1.o main.o
TARGET	= test

all: $(TARGET)

$(TARGET): $(OBJFILES)
	$(CC) $(CFLAGS) -o $(TARGET) $(OBJFILES) $(LDFLAGS)

clean:
	rm -f $(OBJFILES) $(TARGET) *~
