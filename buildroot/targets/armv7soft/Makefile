#
# Copyright (C) 2006-2008 OpenWrt.org
#
# This is free software, licensed under the GNU General Public License v2.
# See /LICENSE for more information.
#
include $(TOPDIR)/rules.mk

ARCH:=arm
BOARD:=armv7soft
BOARDNAME:=Board with armv7 (cortex-a9) SoC
FEATURES:=
LINUX_VERSION:=2.6.36
CPU_TYPE:=cortex-a9

include $(INCLUDE_DIR)/target.mk

define Target/Description
	Build Software Repository for ARM NASes, like QNAP and Synology.
endef

$(eval $(call BuildTarget))
