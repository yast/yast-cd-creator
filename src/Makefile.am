# Makefile.am for cd-creator/src

yncludedir = @yncludedir@/cd-creator

YCPCFLAGS = -I .

client_DATA =			\
	cd-creator.ycp		

ynclude_DATA =			\
	helps.ycp		\
	wizards.ycp		\
	dialogs.ycp		\
	complex.ycp		\
	routines.ycp


desktop_DATA =			\
	cd-creator.desktop

module_DATA =			\
	CDCreator.ycp

EXTRA_DIST = $(client_DATA) $(ynclude_DATA) $(module_DATA) $(desktop_DATA)

include $(top_srcdir)/Makefile.am.common

symlinks:
	test -L cd-creator || ln -sf . cd-creator

ycpchook = symlinks

