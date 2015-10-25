#
# Makefile for sensor chip drivers.
#
CFLAGS_KERNEL	= -fgcse-lm -fgcse-sm -fsched-spec-load -fforce-addr -ffast-math -fsingle-precision-constant -mtune=cortex-a8 -marm -march=armv7-a -mfpu=neon -ftree-vectorize -mvectorize-with-neon-quad

obj-$(CONFIG_THERMAL)		+= thermal_sys.o
