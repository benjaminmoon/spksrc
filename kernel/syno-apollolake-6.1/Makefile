ARCH ?= apollolake
TCVERSION ?= 6.1
PKG_NAME = apollolake
PKG_BRANCH = 15152
PKG_ARCH = $(PKG_NAME)
PKG_EXT = txz
PKG_DIST_NAME = linux-4.4.x.$(PKG_EXT)
PKG_DIST_SITE = https://downloads.sourceforge.net/project/dsgpl/Synology%20NAS%20GPL%20Source/$(PKG_BRANCH)branch/$(PKG_ARCH)-source
PKG_DIST_FILE = $(PKG_NAME)-$(PKG_DIST_NAME)
PKG_EXTRACT = linux-4.4.x
SYNO_CONFIG = synoconfigs/$(ARCH)
BASE_ARCH = x86_64

HOMEPAGE = http://www.synology.com/

include ../../mk/spksrc.kernel-modules.mk
