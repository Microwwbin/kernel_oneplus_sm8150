# SPDX-License-Identifier: GPL-2.0-only
ccflags-y += -mllvm -inline-threshold=15000
ccflags-y += -mllvm -inlinehint-threshold=10000

zram-y	:=	zcomp.o zram_drv.o

obj-$(CONFIG_ZRAM)	+=	zram.o
