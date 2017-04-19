## Process this file with automake to produce Makefile.in

## Created by Anjuta



AM_CPPFLAGS = \
	-DPACKAGE_LOCALE_DIR=\""$(localedir)"\" \
	-DPACKAGE_SRC_DIR=\""$(srcdir)"\" \
	-DPACKAGE_DATA_DIR=\""$(pkgdatadir)"\" \
	$(FILELAUNCHER_CFLAGS)

AM_CFLAGS =\
	 -Wall\
	 -g

bin_PROGRAMS = filelauncher

filelauncher_SOURCES = \
	filelauncher.vala config.vapi

filelauncher_VALAFLAGS =  \
	--pkg gtk+-3.0


filelauncher_LDFLAGS = \
	-Wl,--export-dynamic

filelauncher_LDADD = $(FILELAUNCHER_LIBS)




