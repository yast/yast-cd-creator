# Makefile.am for CD-creator/src

yncludedir = @yncludedir@/CD-creator

client_DATA =			\
	CD-creator.ycp		\
	CD-creator_auto.ycp	\
	CD-creator_proposal.ycp

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
