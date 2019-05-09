.PHONY: all run
all:
	cd ../../abstools; \
	gradle assemble
	../../abstools/frontend/bin/bash/absc -e FileTest.abs

run:
	gen/erl/run
