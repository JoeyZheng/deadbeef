if HAVE_VTX
vtxdir = $(libdir)/$(PACKAGE)
pkglib_LTLIBRARIES = vtx.la
vtx_la_SOURCES = vtx.c ay8912.c ayemu_8912.h ayemu.h ayemu_vtxfile.h lh5dec.c vtxfile.c
vtx_la_LDFLAGS = -module -avoid-version

AM_CFLAGS = $(CFLAGS) -std=c99
endif
