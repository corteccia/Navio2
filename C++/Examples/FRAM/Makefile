CXX ?= g++
TOPDIR = $(CURDIR)/../../Navio
INCLUDES = -I $(TOPDIR)

all:
	$(MAKE) -C $(TOPDIR) all
	$(CXX) $(INCLUDES) FRAM.cpp -L$(TOPDIR) -lnavio -o FRAM

clean:
	rm -f FRAM
