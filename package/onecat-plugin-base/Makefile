include $(TOPDIR)/rules.mk

PKG_NAME:=onecat-plugin-base
PKG_VERSION:=1.0
PKG_RELEASE:=1
PKG_MAINTAINER:=asrtroh-netizen

include $(INCLUDE_DIR)/package.mk

define Package/onecat-plugin-base
  SECTION:=utils
  CATEGORY:=Utilities
  TITLE:=OneCat post-install plugin dependency baseline
  DEPENDS:= \
	+bash \
	+ca-bundle \
	+ca-certificates \
	+curl \
	+wget-ssl \
	+jq \
	+unzip \
	+tar \
	+gzip \
	+bzip2 \
	+xz \
	+zstd \
	+coreutils-base64 \
	+coreutils-nohup \
	+coreutils-stat \
	+coreutils-timeout \
	+diffutils \
	+findutils-find \
	+findutils-xargs \
	+grep \
	+sed \
	+ip-full \
	+tc-tiny \
	+ss \
	+tcpdump \
	+ethtool \
	+ipset \
	+iptables-nft \
	+nftables-json \
	+iptables-mod-extra \
	+iptables-mod-tproxy \
	+kmod-tun \
	+kmod-ifb \
	+kmod-sched-core \
	+kmod-sched-cake \
	+kmod-inet-diag \
	+kmod-netlink-diag \
	+kmod-nft-tproxy \
	+kmod-nft-socket \
	+kmod-ipt-tproxy \
	+kmod-wireguard
endef

define Package/onecat-plugin-base/description
  Shared runtime, archive, network diagnostic, traffic control and
  kernel ABI dependencies commonly reused by post-installed LuCI plugins.
  This package intentionally excludes application-specific services and
  heavyweight language or container runtimes.
endef

define Build/Compile
endef

define Package/onecat-plugin-base/install
	true
endef

$(eval $(call BuildPackage,onecat-plugin-base))
