#
# Copyright (C) 2006-2009 OpenWrt.org
#
# This is free software, licensed under the GNU General Public License v2.
# See /LICENSE for more information.
#
include $(TOPDIR)/rules.mk

ARCH:=arm
BOARD:=s3c64xx
BOARDNAME:=Samsung S3C64xx
FEATURES:=squashfs jffs2 yaffs2
CFLAGS:=-O2 -pipe -march=armv6zk -mtune=arm1176jzf-s -funit-at-a-time
SUBTARGETS:=mini6410 gec6410

LINUX_VERSION:=2.6.36.4

#DEVICE_TYPE=phone

define Target/Description
	S3C64xx arm
endef

include $(INCLUDE_DIR)/target.mk

$(eval $(call BuildTarget))
