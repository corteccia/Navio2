CXX ?= g
CFLAGS = -std=c++11
TOPDIR = $(CURDIR)/../../Navio
INCLUDES = -I $(TOPDIR)

all:
	$(MAKE) -C $(TOPDIR) all
	$(CXX) $(CFLAGS) $(INCLUDES) -L$(TOPDIR) LED.cpp -lnavio -o LED

clean:
	rm -f LED
