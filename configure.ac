AC_INIT([rate4site], [3.0.0], [http://www.tau.ac.il/~itaymay/cp/rate4site.html])
AC_CONFIG_SRCDIR([src/rate4site/rate4site.cpp])

AM_INIT_AUTOMAKE([1.11])
AM_CONFIG_HEADER([config.h])
AC_CONFIG_FILES([Makefile src/phylogeny/Makefile src/rate4site/Makefile])
# Checks for programs.
AC_PROG_CC
if test -z $CXXFLAGS; then
    CXXFLAGS='-O3 -Wno-deprecated'
fi

# use the C++ compiler for the following checks
AC_LANG([C++])

# Checks for header files.
AC_HEADER_STDC
AC_CHECK_HEADERS([string])
AC_CHECK_HEADERS([iostream])

# Checks for typedefs, structures, and compiler characteristics.
AC_TYPE_SIZE_T
AC_PROG_CXX
AC_PROG_CXX
AC_PROG_RANLIB
AC_PROG_INSTALL
AC_PROG_LN_S
AC_PROG_MAKE_SET
AC_OUTPUT
