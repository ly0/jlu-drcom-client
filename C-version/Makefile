objects = drcom.o md5.o

drcom: $(objects)
	gcc -o drcom $(objects)

$(objects):md5.h

.PHONY: clean
clean:
	-rm $(objects)
