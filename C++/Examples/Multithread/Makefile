CXX ?= g++
TOPDIR = $(CURDIR)/../../Navio
INCLUDES = -I $(TOPDIR)

all:
	$(MAKE) -C $(TOPDIR) all
	$(CXX) $(INCLUDES) threaded_baro.cpp -L$(TOPDIR) -lnavio -lpthread -o threaded_baro

clean:
	rm threaded_baro
