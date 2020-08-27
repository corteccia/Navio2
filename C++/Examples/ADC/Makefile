CXX ?= g++
TOPDIR = $(CURDIR)/../../Navio
INCLUDES = -I $(TOPDIR)

all:
	$(MAKE) -C $(TOPDIR) all
	$(CXX) -std=gnu++11 $(INCLUDES)  ADC.cpp -L$(TOPDIR) -lnavio -o ADC

clean:
	rm -f ADC
