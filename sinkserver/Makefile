CXX     :=g++
TARGET  :=sinkserver
SOURCES :=sinkserver.c

all: $(TARGET) $(FILTERSS)

all: $(TARGET)

$(TARGET): $(OBJECTS)
	$(CXX) -pthread $(SOURCES) $^ -o $@

clean:
	rm -f $(TARGET) $(OBJECTS) *.core *~
