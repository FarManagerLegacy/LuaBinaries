![Logo](https://openssl-library.org/images/openssl_logo_library.svg)

Originally, [OpenSSL] is distributed in source form.
However, several trusted third-party binary distributions are also available: https://wiki.openssl.org/index.php/Binaries.

[OpenSSL]: https://openssl-library.org/


Installers
----------

* Shining Light Productions: https://slproweb.com/products/Win32OpenSSL.html
  - The "Light" edition is sufficient (except for development purposes).
  - The *Win64-* installer should be the default choice, but for 32-bit applications *Win32-* may be necessary.
  - Installs the [MS Visual C++ Redistributable][vc_redist].

* FireDaemon: https://www.firedaemon.com/firedaemon-openssl
  - Only x64 installer provided.
  - No external dependencies.

[vc_redist]: https://learn.microsoft.com/cpp/windows/latest-supported-vc-redist#latest-microsoft-visual-c-redistributable-version


Winget packages
---------------

* Shining Light Productions:
  ```
  winget install --id ShiningLight.OpenSSL.Light
  ```
* FireDaemon
  ```
  winget install --id FireDaemon.OpenSSL
  ```
* Force 32-bit installation (available for Shining Light package only)
  ```
  winget install --id ShiningLight.OpenSSL.Light --architecture x86
  ```


Binaries only
-------------

* from _François Piette's_ Internet Component Suite (**ICS**): https://wiki.overbyte.eu/wiki/index.php/ICS_Download#Download_OpenSSL_Binaries
  - Pre-compiled Win32/64 libraries
  - No external dependencies
  
