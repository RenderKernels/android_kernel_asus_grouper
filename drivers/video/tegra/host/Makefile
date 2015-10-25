CFLAGS_KERNEL	= -fgcse-lm -fgcse-sm -fsched-spec-load -fforce-addr -ffast-math -fsingle-precision-constant -mtune=cortex-a8 -marm -march=armv7-a -mfpu=neon -ftree-vectorize -mvectorize-with-neon-quad

GCOV_PROFILE := y
nvhost-objs = \
	nvhost_acm.o \
	nvhost_syncpt.o \
	nvhost_cdma.o \
	nvhost_intr.o \
	nvhost_channel.o \
	nvhost_job.o \
	bus.o \
	dev.o \
	debug.o \
	bus_client.o

obj-$(CONFIG_TEGRA_GRHOST) += mpe/
obj-$(CONFIG_TEGRA_GRHOST) += gr3d/
obj-$(CONFIG_TEGRA_GRHOST) += host1x/
obj-$(CONFIG_TEGRA_GRHOST) += t20/
obj-$(CONFIG_TEGRA_GRHOST) += t30/
obj-$(CONFIG_TEGRA_GRHOST) += dsi/
obj-$(CONFIG_TEGRA_GRHOST) += gr2d/
obj-$(CONFIG_TEGRA_GRHOST) += isp/
obj-$(CONFIG_TEGRA_GRHOST) += vi/
obj-$(CONFIG_TEGRA_GRHOST) += nvhost.o
