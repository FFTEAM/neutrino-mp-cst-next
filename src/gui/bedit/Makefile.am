AM_CPPFLAGS = -fno-rtti -fno-exceptions

AM_CPPFLAGS += \
	-I$(top_builddir) \
	-I$(top_srcdir) \
	-I$(top_srcdir)/src \
	-I$(top_srcdir)/src/zapit/include \
	-I$(top_srcdir)/lib \
	-I$(top_srcdir)/lib/libeventserver \
	-I$(top_srcdir)/lib/libconfigfile \
	-I$(top_srcdir)/lib/xmltree \
	@SIGC_CFLAGS@ \
	@FREETYPE_CFLAGS@ \
	@HWLIB_CFLAGS@

noinst_LIBRARIES = libneutrino_gui_bedit.a

libneutrino_gui_bedit_a_SOURCES = \
	bouqueteditor_bouquets.cpp \
	bouqueteditor_channels.cpp \
	bouqueteditor_chanselect.cpp

