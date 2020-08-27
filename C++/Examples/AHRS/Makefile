CXX ?= g++
CFLAGS = -std=c++11
TOPDIR = $(CURDIR)/../../Navio
INCLUDES = -I $(TOPDIR)

all:
	$(MAKE) -C $(TOPDIR) all
	$(CXX) $(CFLAGS) $(INCLUDES) AHRS.cpp -L$(TOPDIR) -lnavio -o AHRS -lrt -lpthread

clean:
	rm -f AHRS
