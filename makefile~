CC=g++
CFLAGS=-c -Wall
LDFLAGS=
SOURCES=simanneal.cpp
OBJECTS=$(SOURCES:.cpp=.o)
EXECUTABLE=simanneal

all: $(SOURCES) $(EXECUTABLE)
	
$(EXECUTABLE): $(OBJECTS) 
	$(CC) $(LDFLAGS) $(OBJECTS) -o $@

.cpp.o:
	$(CC) $(CFLAGS) $< -o $@

