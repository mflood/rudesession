# Process this file with autoconf to produce a configure script.
#
# Copyright (C) 2005 Matthew Flood
# See file AUTHORS for contact information
#
# This file is part of RudeSession.
#
# RudeSession is free software; you can redistribute it and/or modify
# it under the terms of the GNU General Public License as published by
# the Free Software Foundation; either version 2, or (at your option)
# any later version.
# 
# RudeSession is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.
# 
# You should have received a copy of the GNU General Public License
# along with RudeSession; (see COPYING) if not, write to the Free Software
# Foundation, Inc., 59 Temple Place - Suite 330, Boston, MA
# 02111-1307, USA.
#------------------------------------------------------------------------

AC_INIT(RudeSession, 3.2.2, bug-rudesession@rudeserver.com, rudesession)
AC_CANONICAL_TARGET([])
AM_INIT_AUTOMAKE(rudesession, 3.2.2)

# Checks for programs.
AC_PROG_CXX
AC_PROG_CC
AM_PROG_LIBTOOL

# FIXME: Replace `main' with a function in `-lrudeconfig':
AC_CHECK_LIB([rudeconfig], [main])
# FIXME: Replace `main' with a function in `-lrudeconfig':
AC_CHECK_LIB([rudedatabase], [main])

# Checks for header files.
AC_HEADER_DIRENT
AC_HEADER_STDC
AC_CHECK_HEADERS([stdlib.h string.h unistd.h])


# Checks for typedefs, structures, and compiler characteristics.
AC_C_CONST
AC_C_INLINE
AC_TYPE_SIZE_T

# Checks for library functions.
#AC_CHECK_FUNCS([gethostbyname select socket strerror])
AC_OUTPUT(Makefile )


