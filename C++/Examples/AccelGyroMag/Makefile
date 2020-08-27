CXX ?= g++
TOPDIR = $(CURDIR)/../../Navio
INCLUDES = -I $(TOPDIR)

all:
	$(MAKE) -C $(TOPDIR) all
	$(CXX) -std=c++11 $(INCLUDES) -L$(TOPDIR) AccelGyroMag.cpp -lnavio -o AccelGyroMag

clean:
	rm -f AccelGyroMag
