#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.69])
AC_INIT([FULL-PACKAGE-NAME], [VERSION], [BUG-REPORT-ADDRESS])
AM_INIT_AUTOMAKE ([foreign])
AC_CONFIG_SRCDIR([configc.c])
AC_CONFIG_HEADERS([config.h])

AC_PROG_LIBTOOL

# Checks for programs.
AC_PROG_CC

# Checks for libraries.

# Checks for header files.

# Checks for typedefs, structures, and compiler characteristics.

# Checks for library functions.
AC_CHECK_LIB([json],[json_parse_int64],
    [LIBS="$LIBS -ljson"],
    [AC_MSG_ERROR("libjson not found")]
)

AC_CONFIG_FILES([Makefile])
AC_OUTPUT
