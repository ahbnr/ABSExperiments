.PHONY: all run clean

abstools = ../../../abstools

all:
	cd $(abstools); \
	gradle assemble
	$(abstools)/frontend/bin/bash/absc -e FileTest.abs

run:
	gen/erl/run

clean:
	rm -rf gen
	rm *.dump
