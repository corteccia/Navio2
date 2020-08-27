CXX ?= g++
TOPDIR = $(CURDIR)/../../Navio
INCLUDES = -I $(TOPDIR)

all:
	$(MAKE) -C $(TOPDIR) all
	$(CXX) -std=c++11 $(INCLUDES) AHRS.cpp -L$(TOPDIR) -lnavio -o AHRS -lrt -lpthread

clean:
	rm -f AHRS
