# Apache HTTP Server packaging

This recipe rebuilds the Debian Trixie amd64 source package `apache2` at `2.4.69-1~deb13u1` without downstream patches.

Package CI builds the recipe, verifies a signed APT install, runs an installed-package smoke test, and compares advisory scan results for the distro package and rebuild.
