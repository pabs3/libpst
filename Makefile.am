ACLOCAL_AMFLAGS = -I m4

SUBDIRS = src python man html
htmldir = ${datadir}/doc/@PACKAGE@-@VERSION@
html_DATA = AUTHORS COPYING ChangeLog NEWS README
CLEANFILES = xml/libpst

EXTRA_DIST = Doxyfile xml/header.xml xml/header.sgml xml/libpst.in

if !STATIC_TOOLS
    pkgconfigdir   = $(libdir)/pkgconfig
    pkgconfig_DATA = libpst.pc
endif
