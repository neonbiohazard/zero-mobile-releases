# Zero Mobile Releases

This public repository contains only the signed Zero Mobile APK, the optional signed Ask Zero launcher companion, and signed, non-secret distribution metadata. It contains no application source, account credentials, provider tokens, or developer configuration.

## Required one-time reinstall for legacy alpha builds

Zero Mobile 0.2.136-alpha (build 139) uses Zero's production signing certificate and removes the app's ability to request package-install permission. Android cannot install it over build 138 or any earlier alpha signed with the legacy debug certificate.

If build 138 or an earlier alpha is installed, uninstall both **Zero Mobile** and **Ask Zero**, download the current APKs from this repository, install them through Android's normal system installer, and reconnect the phone to Zero. Future compatible production-signed builds can use the normal update path.
