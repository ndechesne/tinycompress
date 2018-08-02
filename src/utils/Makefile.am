bin_PROGRAMS = cplay crecord

cplay_SOURCES = cplay.c
crecord_SOURCES = crecord.c

cplay_CFLAGS = -I$(top_srcdir)/include \
		    $(AVCODEC_CFLAGS) \
		    $(AVFORMAT_CFLAGS) \
		    $(AVUTIL_CFLAGS) \
		    $(LIBDRM_CFLAGS)

crecord_CFLAGS = -I$(top_srcdir)/include


cplay_LDADD = $(top_builddir)/src/lib/libtinycompress.la \
		    $(AVCODEC_LIBS) \
		    $(AVFORMAT_LIBS) \
		    $(AVUTIL_LIBS) \
		    $(LIBDRM_LIBS)

crecord_LDADD = $(top_builddir)/src/lib/libtinycompress.la
