ACLOCAL_AMFLAGS = -I m4

pkginclude_HEADERS = hiredis.h async.h
adapterincludedir = $(includedir)/hiredis/adapters
adapterinclude_HEADERS = adapters/libevent.h
lib_LTLIBRARIES = libhiredis.la
libhiredis_la_SOURCES = net.c hiredis.c sds.c async.c dict.c
libhiredis_la_CPPFLAGS = -std=c99 -O3 -Wall -pedantic -fPIC -Wwrite-strings
