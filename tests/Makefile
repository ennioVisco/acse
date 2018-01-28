asm=$(CURDIR)/../bin/asm
acse=$(CURDIR)/../bin/acse
export asm acse
dirs:=loop_decreasing
#dirs:=arrays sum dowhile fact mult_table power semi assign arrays arrays2 misc loop_decreasing

test :
	for i in $(dirs); do $(MAKE) -C $$i -f ../Makefile.test ; done

.PHONY : test clean

clean :
	for i in $(dirs); do $(MAKE) -C $$i -f ../Makefile.test clean ; done
