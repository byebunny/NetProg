EXE=main
OBJ=main.o
ISH=main.cpp
FLAGS= -Wall -g


$(EXE): $(OBJ)
	g++ $(FLAGS) $(OBJ) -o $(EXE) 
 
 
$(OBJ): $(ISH) 
	g++ $(FLAGS) -c $(ISH) -o $(OBJ)
     
clean:
	rm -f *.o $(EXE)
