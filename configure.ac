AC_PREREQ([2.60])
AC_INIT([xlibre-xf86-input-elographics],
        [25.0.1],
        [https://github.com/X11Libre/xf86-input-elographics/issues],
        [xlibre-xf86-input-elographics])

XLIBRE_INIT_MODULE_AM(elographics)

# Newer xorg-server.m4 defines this too; keep it for older SDKs.
version_suffix=`echo "$PACKAGE_VERSION" | sed 's/^[[^-]]*//'`
AC_DEFINE_UNQUOTED([PACKAGE_VERSION_SUFFIX], ["$version_suffix"],
                   [Pre-release suffix of the version])

AC_CONFIG_FILES([Makefile src/Makefile man/Makefile man/elographics.man])
AC_OUTPUT
