CXX ?= g++
TOPDIR = $(CURDIR)/../../Navio
INCLUDES = -I $(TOPDIR)

all:
	$(MAKE) -C $(TOPDIR) all
	$(CXX) -std=gnu++11 $(INCLUDES) Servo.cpp -L$(TOPDIR) -lnavio -o Servo

clean:
	rm -f Servo
