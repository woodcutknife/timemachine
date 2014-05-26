#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.69])
AC_INIT([backup], [1.0], [wayne.wangdi@pku.edu.cn])
AM_INIT_AUTOMAKE([foreign])

# Checks for programs.
AC_CHECK_PROG(HAVE_RSYNC,rsync,yes)
if test x"${HAVE_RSYNC}" != x"yes"; then
    AC_MSG_ERROR([Please install rsync first!])
fi

AC_CHECK_PROG(HAVE_SSH,ssh,yes)
if test x"${HAVE_SSH}" != x"yes"; then
    AC_MSG_ERROR([Please install ssh first!])
fi

AC_CHECK_PROG(HAVE_CRONTAB,crontab,yes)
if test x"${HAVE_CRONTAB}" != x"yes"; then
    AC_MSG_ERROR([Please install crontab first!])
fi

AC_CHECK_PROG(HAVE_MD5SUM,md5sum,yes)
if test x"${HAVE_MD5SUM}" != x"yes"; then
    AC_MSG_ERROR([Please install md5sum first!])
fi

AC_CHECK_PROG(HAVE_CUT,cut,yes)
if test x"${HAVE_CUT}" != x"yes"; then
    AC_MSG_ERROR([Please install cut first!])
fi

AC_CHECK_PROG(HAVE_REALPATH,realpath,yes)
if test x"${HAVE_REALPATH}" != x"yes"; then
    AC_MSG_ERROR([Please install realpath first!])
fi

AC_CHECK_PROG(HAVE_DIRNAME,dirname,yes)
if test x"${HAVE_DIRNAME}" != x"yes"; then
    AC_MSG_ERROR([Please install dirname first!])
fi

AC_CHECK_PROG(HAVE_BASENAME,basename,yes)
if test x"${HAVE_BASENAME}" != x"yes"; then
    AC_MSG_ERROR([Please install basename first!])
fi

AC_CHECK_PROG(HAVE_FIND,find,yes)
if test x"${HAVE_FIND}" != x"yes"; then
    AC_MSG_ERROR([Please install find first!])
fi

AC_CHECK_PROG(HAVE_GREP,grep,yes)
if test x"${HAVE_GREP}" != x"yes"; then
    AC_MSG_ERROR([Please install grep first!])
fi

AC_CHECK_PROG(HAVE_XARGS,xargs,yes)
if test x"${HAVE_XARGS}" != x"yes"; then
    AC_MSG_ERROR([Please install xargs first!])
fi

AC_CHECK_PROG(HAVE_SORT,sort,yes)
if test x"${HAVE_SORT}" != x"yes"; then
    AC_MSG_ERROR([Please install sort first!])
fi

AC_CHECK_PROG(HAVE_WC,wc,yes)
if test x"${HAVE_WC}" != x"yes"; then
    AC_MSG_ERROR([Please install wc first!])
fi

AC_CHECK_PROG(HAVE_DATE,date,yes)
if test x"${HAVE_DATE}" != x"yes"; then
    AC_MSG_ERROR([Please install date first!])
fi

AC_CHECK_PROG(HAVE_BASH,bash,yes)
if test x"${HAVE_BASH}" != x"yes"; then
    AC_MSG_ERROR([Please install bash first!])
fi

# Checks for libraries.

# Checks for header files.

# Checks for typedefs, structures, and compiler characteristics.

# Checks for library functions.

AC_CONFIG_FILES([Makefile])
AC_OUTPUT
