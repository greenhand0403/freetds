AM_CPPFLAGS	= -I$(top_srcdir)/include 

if !MINGW32
bin_PROGRAMS	= fisql

fisql_SOURCES	= fisql.c  \
		terminal.h terminal.c  \
		edit.h edit.c  \
		handlers.h handlers.c  \
		interrupt.h interrupt.c
		

fisql_LDADD	= ../../dblib/libsybdb.la \
		  ../../replacements/libreplacements.la \
		  $(LTLIBICONV) $(READLINE_LIBS)
endif
