.PHONY = all clean
SRCDIR = ./spl_progs
SPL = ./spl

SRCS := $(shell find $(SRCDIR) -type f -name *.spl)
BINS := $(SRCS:%.spl=%.xsm)

all: ${BINS}
	
%.xsm: %.spl
	${SPL} $<