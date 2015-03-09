#Owned by DairyMan@Whirlpool
#
#Copyright GNU act.
include $(TOPDIR)/rules.mk

PKG_NAME:=ext-rooter4
PKG_VERSION:=1.000
PKG_RELEASE:=1

PKG_MAINTAINER:=Created by DM/makefile by Cobia@whirlpool
include $(INCLUDE_DIR)/package.mk

define Package/ext-rooter4
  SECTION:=utils
  CATEGORY:=Network
  DEPENDS:=+luci
  TITLE:=Install ext-rooter4
  PKGARCH:=all
endef

define Package/ext-rooter4/description
  Helper scripts to install ext-rooter4
endef


define Build/Compile
endef

define Package/ext-rooter4/install
	$(CP) ./files/* $(1)/


endef

$(eval $(call BuildPackage,ext-rooter4))
