include $(TOPDIR)/rules.mk

PKG_NAME:=luci-app-kidcontrol
PKG_VERSION:=1.0
PKG_RELEASE:=1
PKG_MAINTAINER:=holyhbc <holyhbc@gmail.com>
PKG_LICENSE:=GPL-2.0
PKG_ARCH:=all

LUCI_TITLE:=LuCI support for Kid Control
LUCI_DEPENDS:=+nftables
LUCI_PKGARCH:=all

include $(TOPDIR)/feeds/luci/luci.mk

# 生成 package
$(eval $(call BuildPackage,luci-app-kidcontrol))
