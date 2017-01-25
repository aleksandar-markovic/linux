#
# Makefile for Goldfish virtual platform
#

ccflags-y += -Wno-error

CFLAGS_goldfish-platform.o	= -I$(src)/../../../scripts/dtc/libfdt

obj-$(CONFIG_GOLDFISH)	+= goldfish-platform.o
obj-$(CONFIG_GOLDFISH)	+= goldfish-interrupt.o
obj-$(CONFIG_GOLDFISH)	+= goldfish-time.o
obj-$(CONFIG_GOLDFISH)	+= goldfish-rtc.o
obj-$(CONFIG_GOLDFISH)	+= pm.o
obj-$(CONFIG_GOLDFISH)  += goldfish-reset.o
