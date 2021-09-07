AUTOMAKE_OPTIONS = foreign
ACLOCAL_AMFLAGS = -I m4

AM_CLAGS = $(CFLAGS) -D_GNU_SOURCE -I.

lib_LTLIBRARIES = libwiringpi.la
libwiringpi_la_SOURCES = wiringPi.c softTone.c softPwm.c

EXTRA_DIST = wiringPi.h softTone.h softPwm.h ../version.h
