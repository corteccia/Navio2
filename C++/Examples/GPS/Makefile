CXX ?=g++
CFLAGS=-c -Wall
TOPDIR = $(CURDIR)/../../Navio
INCLUDES = -I $(TOPDIR)

all:
	$(MAKE) -C $(TOPDIR) all
	$(CXX) -std=c++11 $(INCLUDES) gps.cpp -L$(TOPDIR) -lnavio -o
	rm -rf *.o

clean:
	rm -rf *.o gps
