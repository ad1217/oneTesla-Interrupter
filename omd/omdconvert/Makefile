all: omdconvert

LDFLAGS=-Limprov/lib -s
LDLIBS=-limprov

omdconvert: improv/lib/libimprov.a

improv/lib/libimprov.a: improv
	make -C improv library

clean-improv:
	make -C improv clean

clean:
	rm omdconvert
