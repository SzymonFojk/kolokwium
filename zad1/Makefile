FLAGS = -Wall

myProgram: main.cpp address.o employee.o
	g++ $(FLAGS) -o $@ $< -lm address.o employee.o
%.o : %.cpp %.h
	g++ $(FLAGS) -c $< -lm
clean:
	rm -rf *.o myProgram
