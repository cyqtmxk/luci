include $(TOPDIR)/rules.mk

LUCI_TITLE:=Docker Manager interface for LuCI
LUCI_DEPENDS:=+luci-lib-docker +luci-lib-ip +docker +dockerd +ttyd
LUCI_PKGARCH:=all

PKG_NAME:=luci-app-dockerman
PKG_VERSION:=v0.5.25
PKG_RELEASE:=1

PKG_LICENSE:=AGPL-3.0
PKG_MAINTAINER:=lisaac <lisaac.cn@gmail.com>



include ../../luci.mk

# call BuildPackage - OpenWrt buildroot signature
