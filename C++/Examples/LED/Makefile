CXX ?= g++
TOPDIR = $(CURDIR)/../../Navio
INCLUDES = -I $(TOPDIR)
CFLAGS = -std=c++11

all:
	$(MAKE) -C $(TOPDIR) all
	$(CXX) $(CFLAGS) $(INCLUDES) -L$(TOPDIR) LED.cpp -lnavio -o LED

clean:
	rm -f LED
