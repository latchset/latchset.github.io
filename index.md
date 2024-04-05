![banner](profile/latchset-banner.png)

# Welcome to Latchset

The latchset organization hosts projects related to applications or libraries
for use in cryptography or security context and primarily targeted at Linux
and Unix-like operating systems.

## [Clevis & Tang](./clevistang/)

[Clevis](https://github.com/latchset/clevis) is a plugable framework for
automated decryption. It can be used to provide automated decryption of
data or even automated unlocking of LUKS volumes. 
[Tang](https://github.com/latchset/tang) is a server for binding data to network presence.


## [Custodia](./custodia/)

[Custodia](https://github.com/latchset/custodia) is a service to manage,
retrieve and store secrets.


## [Javascript Object Signing and Encryption (JOSE)](./jose/)

[josé](https://github.com/latchset/jose) is a C-language implementation
of the Javascript Object Signing and Encryption standards with plugable
backends. [pyjose](https://github.com/latchset/pyjose) provides bindings
for Python.

[jwcrypto](https://github.com/latchset/jwcrypto) is a pure Python
implementation of JOSE on top of 
[PyCA cryptography](https://github.com/pyca/cryptography).

## [KDC Proxy (Kerberos over HTTPS)](./kdcproxy/)

[kdcproxy](https://github.com/latchset/kdcproxy) is a WSGI module for
proxying Kerberos KDC requests over HTTPS by following the MS-KKDCP protocol
specification.


## [libverto (verto)](./libverto/)

[libverto](https://github.com/latchset/libverto) is an asynchronous event loop
abstraction library.  It provides a C interface which is backend-agnostic, as
well as several backends, and can select a provider at either compile-time or
run-time.


## [misc](./misc/)

Misc and experimental projects. 


## [pkcs11](./pkcs11/)

Projects related to the [PKCS#11](https://www.oasis-open.org/committees/pkcs11/) standard

[pkcs11-provider](https://github.com/latchset/pkcs11-provider) is an OpenSSL
provider module to allow applications linking to OpenSSL to transparently
use PKCS#11 tokens for cryptographic operations.

[pkcs11-headers](https://github.com/latchset/pkcs11-headers) an Open Source
licensing friendly rewrite of pkcs11 headers for C applications.

[kryoptic](https://github.com/latchset/kryoptic) a Cryptoki software
token written in Rust implementing the latest PKCS#11 API version.

