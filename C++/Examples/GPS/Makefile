CXX ?=g++
CFLAGS = -std=c++11
TOPDIR = $(CURDIR)/../../Navio
INCLUDES = -I $(TOPDIR)

all:
	$(MAKE) -C $(TOPDIR) all
	$(CXX) $(CFLAGS) $(INCLUDES) gps.cpp -L$(TOPDIR) -lnavio -o gps
	rm -rf *.o

clean:
	rm -rf *.o gps
