# SPDX-License-Identifier: GPL-2.0
dtb-$(CONFIG_ARCH_BCM2835) += bcm2837-rpi-3-b.dtb
dtb-$(CONFIG_ARCH_BCM2709) += bcm2710-rpi-3-b.dtb
dtb-$(CONFIG_ARCH_BCM2835) += bcm2710-rpi-3-b.dtb
dtb-$(CONFIG_ARCH_BCM2835) += bcm2710-rpi-3-b-plus.dtb

# Enable fixups to support overlays on BCM2835 platforms
ifeq ($(CONFIG_ARCH_BCM2835),y)
	DTC_FLAGS ?= -@
endif

subdir-y	+= northstar2
subdir-y	+= stingray
