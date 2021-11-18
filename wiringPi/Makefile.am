AUTOMAKE_OPTIONS = foreign
ACLOCAL_AMFLAGS = -I m4

AM_CPPFLAGS = $(CFLAGS) -D_GNU_SOURCE -I.

lib_LTLIBRARIES = libwiringpi.la
libwiringpi_la_SOURCES = wiringPi.c softTone.c softPwm.c piHiPri.c
if ENABLE_WP_SPI
libwiringpi_la_SOURCES += wiringPiSPI.c
endif
libwiringpi_la_LDFLAGS = -version-info 0:0:0

EXTRA_DIST = wiringPi.h softTone.h softPwm.h ../version.h
if ENABLE_WP_SPI
EXTRA_DIST += wiringPiSPI.h
endif
