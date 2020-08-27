CXX ?= g++
CFLAGS = -std=gnu++11
TOPDIR = $(CURDIR)/../../Navio
INCLUDES = -I $(TOPDIR)

all:
	$(MAKE) -C $(TOPDIR) all
	$(CXX) $(CFLAGS) $(INCLUDES) Servo.cpp -L$(TOPDIR) -lnavio -o Servo

clean:
	rm -f Servo
