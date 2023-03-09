CC=g++
CFLAGS=-c -Wall -Wextra -Wpedantic -Wconversion -Wsign-conversion
LDFLAGS=-L../lib -I../include
SOURCES=src/*.cpp
OBJECTS=$(SOURCES:.cpp=.o)
EXECUTABLE=jotml

all: $(SOURCES) $(EXECUTABLE)

$(EXECUTABLE): $(OBJECTS)
    $(CC) $(LDFLAGS) $(OBJECTS) -o $@

.cpp.o:
    $(CC) $(CFLAGS) $< -o $@

clean:
    rm -f $(OBJECTS) $(EXECUTABLE)
