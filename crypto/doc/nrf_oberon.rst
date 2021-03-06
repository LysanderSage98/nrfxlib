.. _nrf_oberon_readme:

nrf_oberon crypto library
#########################

The nrf_oberon library contains a collection of cryptographic algorithms created by Oberon Microsystems, licensed to Nordic Semiconductor ASA for redistribution.
The library provides highly optimized software for Nordic Semiconductor SoCs based on Cortex-M0, Cortex-M4, and Cortex-M33 architectures.


Supported cryptographic algorithms
==================================
* AES CTR, EAX, GCM
* ChaCha20-Poly1035
* ECDH using curve NIST secp256r1
* ECDSA sign and verify using curve NIST secp256r1
* Ed25519
* HKDF using SHA-256 and SHA-512
* HMAC using SHA-256 and SHA-512
* RSA PKCS#1 v1.5 and v2.1 (1024, 2048 bits)
* SHA-256
* SHA-512
* SRP
* SRTP


Initializing the library
========================
The library does not require any initialization before the APIs can be used, although some APIs require calling specific initialization functions before use.


nrf_oberon crypto library
=========================
:ref:`crypto_api_nrf_oberon`