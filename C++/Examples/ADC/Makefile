CXX ?= g++
CFLAGS = -std=gnu++11
TOPDIR = $(CURDIR)/../../Navio
INCLUDES = -I $(TOPDIR)

all:
	$(MAKE) -C $(TOPDIR) all
	$(CXX) $(CFLAGS) $(INCLUDES)  ADC.cpp -L$(TOPDIR) -lnavio -o ADC

clean:
	rm -f ADC
