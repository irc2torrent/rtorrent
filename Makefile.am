SUBDIRS = \
	doc \
	src \
	test

nobase_dist_pkgdata_DATA = \
	lua/rtorrent.lua

EXTRA_DIST= \
	scripts/checks.m4 \
	scripts/common.m4 \
	scripts/attributes.m4

# The macro directory is declared by AC_CONFIG_MACRO_DIRS in configure.ac.
# Repeating it here as ACLOCAL_AMFLAGS is redundant, and libtool 2.5.4 makes
# the duplicate a fatal libtoolize error.
