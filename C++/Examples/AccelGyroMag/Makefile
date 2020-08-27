CXX ?= g++
CFLAGS = -std=c++11
TOPDIR = $(CURDIR)/../../Navio
INCLUDES = -I $(TOPDIR)

all:
	$(MAKE) -C $(TOPDIR) all
	$(CXX) $(CFLAGS) $(INCLUDES) -L$(TOPDIR) AccelGyroMag.cpp -lnavio -o AccelGyroMag

clean:
	rm -f AccelGyroMag
