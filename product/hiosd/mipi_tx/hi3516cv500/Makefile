#MIPI_TX_PATH := $(srctree)/product/hiosd/mipi_tx

ARCH_NAME := hi3516cv500

cflags-y += -I$(srctree)/product/hiosd/mipi_tx/$(ARCH_NAME)
cflags-y += -I$(srctree)/product/hiosd/mipi_tx/$(ARCH_NAME)/include
cflags-y += -I$(srctree)/product/hiosd/mipi_tx/$(ARCH_NAME)/hal

cflags-y     += -I$(srctree)/include

ccflags-y  += $(cflags-y)
HOSTCFLAGS += $(cflags-y)
CPPFLAGS   += $(cflags-y)

obj-y += ./mipi_tx_hal.o
obj-y += ./mipi_tx.o
