.PHONY: all run clean

abstools = ../../../abstools

all:
	$(abstools)/frontend/bin/bash/absc -e TypeTest.abs

run:
	gen/erl/run

clean:
	rm -rf gen
	rm *.dump
