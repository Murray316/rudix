include ../../Library/GNU.mk

Title=		GNU Hello
Name=		hello
Version=	2.10
Site=		http://www.gnu.org/software/hello/
Source=		http://ftp.gnu.org/gnu/hello/$(Name)-$(Version).tar.gz
License=	GPL

define test_hook
$(BinDir)/hello --version | grep $(Version)
endef
