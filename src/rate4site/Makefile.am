rate4sitedir=usr/share/rate4site
rate4site_doublerepdir=usr/share/rate4site

PROGS=rate4site rate4site_doublerep

bin_PROGRAMS=$(PROGS)

AM_CXXFLAGS = -I$(top_srcdir)/src/phylogeny/ 

rate4site_doublerep_CPPFLAGS = -DDOUBLEREP  

rate4site_LDADD = ../../src/phylogeny/libphylo.a
rate4site_doublerep_LDADD = ../../src/phylogeny/libphylo_doublerep.a

rate4site_HEADERS = \
	rate4site.h \
	rate4siteOptions.h  


rate4site_SOURCES = \
	rate4siteOptions.cpp \
	rate4site.cpp 

rate4site_doublerep_HEADERS = \
		rate4site.h \
		rate4siteOptions.h  

rate4site_doublerep_SOURCES = \
		rate4siteOptions.cpp \
		rate4site.cpp 
