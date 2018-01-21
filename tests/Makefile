asm=$(CURDIR)/../bin/asm
acse=$(CURDIR)/../bin/acse
export asm acse
dirs:=arrays sum dowhile fact mult_table power semi assign arrays arrays2 misc
custom_dirs:= foreach-every

test :
	for i in $(custom_dirs); do $(MAKE) -C $$i -f ../Makefile.test ; done

.PHONY : test clean

clean :
	for i in $(custom_dirs); do $(MAKE) -C $$i -f ../Makefile.test clean ; done
