
EXE=exit
OBJ=exit.o

$(EXE): $(OBJ)
	ld $(OBJ) -o $@

$(OBJ): ret_val.s
	as ret_val.s -o $(OBJ)

clean:
	rm $(OBJ) $(EXE)

.PHONY:
	clean

