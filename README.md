# NIST, IETF, IRTF specification standards

The Transport Layer Security (TLS) Protocol Version 1.3
https://tools.ietf.org/html/draft-ietf-tls-tls13-12#section-8

NIST SP 800-56: Recommendation for Pair-Wise Key Establishment Schemes Using Discrete Logarithm Cryptography, July 2005, DRAFT
https://csrc.nist.gov/CSRC/media/Publications/sp/800-56a/archive/2006-05-03/documents/sp800-56-draft-jul2005.pdf#page53

Internet Key Exchange Protocol IKEv2 with Curve25519 and Curve448
https://tools.ietf.org/html/rfc8031

Curve25519 Daniel Bernstein Eliptical curve white paper
https://ed25519.cr.yp.to/ed25519-20110705.pdf

Curve25519 Java example usage
http://openjdk.java.net/jeps/324

Curve25519 and Curve448 IRTF specification
https://tools.ietf.org/html/rfc7748

OpenSSL X25519:

    openssl genpkey -algorithm X25519 -out privkey.pem
  
    openssl pkey -in privkey.pem -pubout -out pubkey.pem




