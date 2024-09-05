
SRC=max_num.s
MAXOBJ=max.o
MAXBIN=max

$(MAXBIN): $(MAXOBJ)
	ld -o $@ $<

$(MAXOBJ): $(SRC)
	as -o $@ $<

clean:
	rm $(MAXOBJ) $(MAXBIN)

.PHOMY:
	clean
