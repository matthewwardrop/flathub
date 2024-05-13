# Immersed Desktop Agent

This is an unofficial Flatpak repackaging of the official AppImage, which should
better integrate into your existing applications. Please do not report issues
that only affect the Flatpak package to Immersed.

**Note:** The upstream appimage is downloaded during the install phase of this
Flatpak. This package does not itself contain any upstream code.

**Known issues:**

* If this package falls behind its upstream counterpart, installation will fail
  due to a mismatch in sha256sums (since Immersed does not provide stable URLs
  for historical versions of the app).