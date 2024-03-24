# Trusted Publishers in PyPI

[![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

Trusted publishing is a "new" mechanism for uploading packages to the
Python Package Index (PyPI).

It leverages the OpenID Connect (OIDC) standard to facilitate the exchange
of short-lived identity tokens between a trusted third-party service and
PyPI. What's cool about this method is its applicability in automated
environments (like GitHub Actions), offering a streamlined process that
removes the need for manually generated API tokens for authentication
for your publishing workflows.

##  License

This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
