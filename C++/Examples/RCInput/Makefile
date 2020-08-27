CXX ?= g++
TOPDIR = $(CURDIR)/../../Navio

PIGPIO_PATH ?= $(TOPDIR)/pigpio

LIB = -L$(PIGPIO_PATH)

INCLUDES = -I $(TOPDIR) -I$(PIGPIO_PATH)

all:
	$(MAKE) -C $(TOPDIR) all
	$(CXX) -std=gnu++11 $(INCLUDES) $(LIB) RCInput.cpp -L$(TOPDIR) -lnavio -o RCInput -lrt -lpthread -lpigpio

clean:
	rm -f RCInput
