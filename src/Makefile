CC = g++
CFLAGS = -std=c++17
SRC = main.cpp
EXEC = program
OBJ = $(SRC:.cpp=.o)
all:
	@echo "Build Complete"

$(EXEC):$(OBJ)
	$(CC) $(OBJ) -o $@a
%.o: %.cpp
	$(CC) $(CFLAGS) -c $< -o $@

clean:
	rm -f $(EXEC)
	rm -f $(OBJ)
