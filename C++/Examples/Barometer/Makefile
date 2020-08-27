CXX ?= g++
TOPDIR = $(CURDIR)/../../Navio
INCLUDES = -I $(TOPDIR)

all:
	$(MAKE) -C $(TOPDIR) all
	$(CXX) $(INCLUDES) Barometer.cpp -L$(TOPDIR) -lnavio -o Barometer

clean:
	rm -f Barometer
