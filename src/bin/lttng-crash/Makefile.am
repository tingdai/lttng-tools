AM_CPPFLAGS = -I$(top_srcdir)/include -I$(top_srcdir)/src \
			  -DINSTALL_BIN_PATH=\""$(bindir)"\"

bin_PROGRAMS = lttng-crash

lttng_crash_SOURCES = lttng-crash.c

lttng_crash_LDADD = $(top_builddir)/src/common/libcommon.la \
			$(top_builddir)/src/common/config/libconfig.la
