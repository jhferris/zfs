include $(top_srcdir)/config/Rules.am

AM_CFLAGS += $(DEBUG_STACKFLAGS) $(FRAME_LARGER_THAN)

DEFAULT_INCLUDES += \
	-I$(top_srcdir)/include \
	-I$(top_srcdir)/lib/libspl/include

lib_LTLIBRARIES = libavl.la

libavl_la_SOURCES = \
	$(top_srcdir)/module/avl/avl.c

libavl_la_LDFLAGS = -version-info 1:0:0
