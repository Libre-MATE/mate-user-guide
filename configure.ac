#   Copyright (C) 2022  Libre MATE
#
# This library is free software; you can redistribute it and/or
# modify it under the terms of the GNU Lesser General Public
# License as published by the Free Software Foundation; either
# version 2.1 of the License, or (at your option) any later version.
#
# This library is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU
# Lesser General Public License for more details.
#
# You should have received a copy of the GNU Lesser General Public
# License along with this library; if not, write to the Free Software
# Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston, MA  02110-1301  USA

AC_INIT([mate-user-guide],
        [1.26.0],
        [https://github.com/Libre-MATE/mate-user-guide/issues],
        [mate-user-guide],
        [https://github.com/Libre-MATE/mate-user-guide/])
AC_COPYRIGHT([Copyright (C) 2022 Libre MATE])
AM_INIT_AUTOMAKE([1.11 dist-xz no-dist-gzip silent-rules])
AM_MAINTAINER_MODE([enable])

GETTEXT_PACKAGE=AC_PACKAGE_NAME
AC_DEFINE_UNQUOTED(GETTEXT_PACKAGE, "$GETTEXT_PACKAGE", [The gettext translation domain])
AC_SUBST(GETTEXT_PACKAGE)

AM_GNU_GETTEXT([external])
AM_GNU_GETTEXT_VERSION([0.19.8])
AM_GNU_GETTEXT_REQUIRE_VERSION([0.19.8])
AM_CONDITIONAL([USE_NLS], [test "x${USE_NLS}" = "xyes"])

YELP_HELP_INIT

AC_CONFIG_FILES([
Makefile
mate-user-guide.desktop.in
po/Makefile.in
mate-user-guide/Makefile
])

AC_OUTPUT

echo "
Configure summary:

	${PACKAGE_STRING}
	`echo $PACKAGE_STRING | sed "s/./=/g"`

	Native Language support.....:  ${USE_NLS}
"
