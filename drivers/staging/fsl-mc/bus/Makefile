#
# Freescale Management Complex (MC) bus drivers
#
# Copyright (C) 2014 Freescale Semiconductor, Inc.
#
# This file is released under the GPLv2
#
obj-$(CONFIG_FSL_MC_BUS) += mc-bus-driver.o

mc-bus-driver-objs := fsl-mc-bus.o \
		      mc-sys.o \
		      mc-io.o \
		      dprc.o \
		      dpmng.o \
		      dprc-driver.o \
		      fsl-mc-allocator.o \
		      fsl-mc-msi.o \
		      irq-gic-v3-its-fsl-mc-msi.o \
		      dpmcp.o \
		      dpbp.o \
		      dpcon.o \
		      fsl-mc-iommu.o

# MC DPIO driver
obj-$(CONFIG_FSL_MC_DPIO) += dpio/

# MC restool kernel support
obj-$(CONFIG_FSL_MC_RESTOOL) += mc-restool.o
