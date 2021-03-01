AUTOMAKE_OPTIONS = foreign

CFLAGS = -Wall -pedantic -O2
include_HEADERS = bbexample.h

lib_LTLIBRARIES = libexapp.la
libbbexample_la_SOURCES  = exapplib.c
libbbexample_la_LDFLAGS= -version-info 1:0:0

bin_PROGRAMS = exapp
bbexample_SOURCES = exapp.c
bbexample_LDADD = libexapp.la
