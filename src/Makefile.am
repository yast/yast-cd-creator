# Makefile.am for CD-creator/src

yncludedir = @yncludedir@/CD-creator

client_DATA =			\
	CD-creator.ycp		

ynclude_DATA =			\
	helps.ycp		\
	wizards.ycp		\
	dialogs.ycp		\
	complex.ycp		\
	routines.ycp


desktop_DATA =			\
	CD-creator.desktop

module_DATA =			\
	CDCreator.ycp

EXTRA_DIST = $(client_DATA) $(ynclude_DATA) $(module_DATA) $(desktop_DATA)

include $(top_srcdir)/Makefile.am.common

symlinks:
	test -L CD-creator || ln -sf . CD-creator

ycpchook = symlinks

