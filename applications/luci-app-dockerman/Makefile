include $(TOPDIR)/rules.mk

LUCI_TITLE:=LuCI Support for docker
LUCI_DEPENDS:=@(aarch64||arm||x86_64||riscv64) \
	+luci-compat \
	+luci-lib-docker \
	+docker \
	+ttyd
LUCI_PKGARCH:=all

PKG_LICENSE:=AGPL-3.0
PKG_MAINTAINER:=lisaac <lisaac.cn@gmail.com> \
		Florian Eckert <fe@dev.tdt.de>

PKG_VERSION:=v0.5.13-20230114

include ../../luci.mk

# call BuildPackage - OpenWrt buildroot signature
