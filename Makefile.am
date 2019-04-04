AM_CXXFLAGS = \
	$(WARN_CFLAGS)	\
	-I${includedir} \
	-I${includedir}/libxml2

libnx_config_la_LTLIBRARIES = libnx_config.la
libnx_config_ladir = ${libdir}
libnx_config_la_LDFLAGS = -L${libdir} -lxml2

libnx_config_la_SOURCES = \
	NX_CConfig.cpp

libnx_config_includedir = ${includedir}
libnx_config_include_HEADERS = \
	NX_IConfig.h
