# Makefile.am
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

lib_LTLIBRARIES = librudesession.la

librudesession_la_SOURCES = 		src/Implementation.cpp \
	src/Implementation.h \
	src/Session.cpp \
	src/session.h \
	src/Cookie.cpp \
	src/Cookie.h \
	src/CookieParser.cpp \
	src/CookieParser.h \
	src/CookieReader.cpp \
	src/CookieReader.h \
	src/AbstractData.cpp \
	src/AbstractData.h \
	src/Configuration.cpp \
	src/Configuration.h \
	src/DataStore.cpp \
	src/DataStore.h \
	src/MetaData.cpp \
	src/MetaData.h \
	src/AbstractPersistance.cpp \
	src/AbstractPersistance.h \
	src/ConfigFilePersistance.cpp \
	src/ConfigFilePersistance.h \
	src/DatabasePersistance.cpp \
	src/DatabasePersistance.h \
	src/Base64Encoder.cpp \
	src/Base64Encoder.h \
	src/Converter.cpp \
	src/Converter.h \
	src/IDGenerator.cpp \
	src/IDGenerator.h \
	src/IPValidator.cpp \
	src/IPValidator.h

librudesession_la_LDFLAGS = -version-info 3:2:1

#  -------------------------------------
librudesession_la_LIBADD = -lrudeconfig -lrudedatabase
#----------------------------------------

pkginclude_HEADERS = src/session.h
pkgincludedir = $(includedir)/rude

man_MANS = man3/rudesession.3

EXTRA_DIST = $(man_MANS)

AUTOMAKE_OPTIONS = gnits dist-bzip2 dist-shar dist-zip


