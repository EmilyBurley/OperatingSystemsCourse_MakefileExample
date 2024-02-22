# Set the C compiler to gcc.
CC	= gcc

# For the C flags, choose the -Wall option, which enables most warning
# messages to help catch potential issues in the code.
CFLAGS	= -Wall

# Set no linker flags.
LDFLAGS	=

# Set object files that will be used to create the final executable.
OBJFILES	= f1.o main.o

# Specify the name of the final executable.
MAIN_TARGET	= main
TASK_TARGET	= task

# Define a target named "all" that depends on the target specified by
# the TARGET variable. In this case, it means that running "make all"
# will build the "test" target.
all: $(MAIN_TARGET) $(TASK_TARGET)

# Make a rule to build the target specified by the TARGET variable.
# It depends on the object files listed in OBJFILES. The rule uses the
# gcc compiler ("$(CC)") with the flags specified in CFLAGS to link the
# object files into the final executable.
$(MAIN_TARGET): main.c
	$(CC) $(CFLAGS) main.c -o $(MAIN_TARGET)
$(TASK_TARGET): task.c
	$(CC) $(CFLAGS) task.c -o $(TASK_TARGET)

# Make a rule to clean up the project. Running "make clean" will remove
# the object files, the target executable, and any backup files denoted
# by "*~" (commonly used by text editors).
clean:
##	rm -f $(OBJFILES) $(TARGET) *~
