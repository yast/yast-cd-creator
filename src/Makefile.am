# Makefile.am for cd-creator/src
#
#
SUBDIRS = data

yncludedir = @yncludedir@/cd-creator

YCPCFLAGS = -I ./include

client_DATA =			\
	cd-creator.ycp		

ynclude_DATA =			\
	helps.ycp		\
	wizards.ycp		\
	dialogs.ycp		\
	complex.ycp		\
	routines.ycp		\
	kiwi.ycp


desktop_DATA =			\
	cd-creator.desktop

module_DATA =			\
	CDCreator.ycp	

EXTRA_DIST = $(client_DATA) $(ynclude_DATA) $(module_DATA) $(desktop_DATA)

include:
	mkdir include && ln -sf ../ include/cd-creator

ycpchook = include

include $(top_srcdir)/Makefile.am.common



