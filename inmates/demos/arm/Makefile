#
# Jailhouse, a Linux-based partitioning hypervisor
#
# Copyright (c) ARM Limited, 2014
#
# Authors:
#  Jean-Philippe Brucker <jean-philippe.brucker@arm.com>
#
# This work is licensed under the terms of the GNU GPL, version 2.  See
# the COPYING file in the top-level directory.
#

include $(INMATES_LIB)/Makefile.lib

INMATES := gic-demo.bin uart-demo.bin sun-app.bin

gic-demo-y	:= gic-demo.o
uart-demo-y	:= uart-demo.o
sun-app-y	:= sun-app.o

$(eval $(call DECLARE_TARGETS,$(INMATES)))
