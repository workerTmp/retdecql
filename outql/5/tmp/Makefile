    iEdit: $(patsubst %.cpp,%.o,$(wildcard *.cpp))
        -gcc $^ -o $@ 

    %.o: %.cpp
        -gcc -c $