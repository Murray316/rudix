include ../../Library/Unix.mk
ifeq ($(OSXVersion),10.6)
RUDIX_UNIVERSAL=
endif

Title=		LuaJIT
Name=		luajit
Version=	2.0.4
Site=		http://luajit.org/
Source=		http://luajit.org/download/LuaJIT-$(Version).tar.gz
License=	MIT

LicenseFile=	$(SourceDir)/COPYRIGHT

define test_hook
$(BinDir)/luajit -v | grep $(Version)
endef
