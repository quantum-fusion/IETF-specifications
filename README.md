#
# Quantum-fusion center for Advanced Cryptography Standards, established Circa July 2018
#

# NIST/IETF Standards and Internet protocols

[1] IETF Worldwide search and statistics tracking
https://www.arkko.com/tools/docstats.html

[2] Internet Key Exchange Protocol IKEv2 with Curve25519 and Curve448
https://tools.ietf.org/html/rfc8031

[3] CFRG Elliptic Curve Diffie-Hellman (ECDH) and Signatures in JSON Object Signing and Encryption (JOSE), January 2017
https://tools.ietf.org/html/rfc8037

[4] HMAC-based Extract-and-Expand Key Derivation Function (HKDF)
https://tools.ietf.org/html/rfc5869

[5] Mozilla Java Security (HKDF and FIPS)
https://github.com/mozilla-services
https://github.com/mozilla-services/sync-crypto/blob/master/src/main/java/org/mozilla/android/sync/crypto/HKDF.java
https://github.com/quantum-fusion/jss/blob/master/org/mozilla/jss/tests/FipsTest.java
https://github.com/quantum-fusion/jss/tree/master/org/mozilla/jss/tests

[6] Amazon Web Services DynamoDb HKDF 
https://github.com/awslabs/aws-dynamodb-encryption-java/blob/master/src/main/java/com/amazonaws/services/dynamodbv2/datamodeling/internal/Hkdf.java

[7] The Transport Layer Security (TLS) Protocol Version 1.3
https://tools.ietf.org/html/draft-ietf-tls-tls13-12#section-8

[8] NIST SP 800-56: Recommendation for Pair-Wise Key Establishment Schemes Using Discrete Logarithm Cryptography, July 2005, DRAFT
- KDF2 key generation 
https://csrc.nist.gov/CSRC/media/Publications/sp/800-56a/archive/2006-05-03/documents/sp800-56-draft-jul2005.pdf#page53

[9] Message Encryption for Web Push
https://tools.ietf.org/html/rfc8291

[10] Simple Certificate Enrolment Protocol, draft-gutmann-scep-06
https://tools.ietf.org/id/draft-gutmann-scep-06.html

[11] Simple Certificate Enrollment Protocol, draft-nourse-scep-23
https://tools.ietf.org/html/draft-nourse-scep-23

[12] The Double Ratchet Algorithm, Revision 1, 2016-11-20, by Trevor Perrin (editor), Moxie Marlinspike
https://signal.org/docs/specifications/doubleratchet/
https://signal.org/docs/specifications/doubleratchet/doubleratchet.pdf

[13] Curve25519 Daniel Bernstein Eliptical curve white paper
https://ed25519.cr.yp.to/ed25519-20110705.pdf

[14] Curve25519 Java example usage
http://openjdk.java.net/jeps/324

[15] Curve25519 and Curve448 IRTF specification
https://tools.ietf.org/html/rfc7748

[16] Apple's List of available trusted root certificates in iOS 11
https://support.apple.com/en-us/HT208125

[17] Elliptic Curve Cryptography (ECC) in OpenPGP
https://tools.ietf.org/html/rfc6637

[18] Edwards-Curve Digital Signature Algorithm (EdDSA)
https://tools.ietf.org/html/rfc8032

[19] Dynamic Symmetric Key Provisioning Protocol (DSKPP), draft-ietf-keyprov-dskpp-14.txt, Sept 7 2010
https://tools.ietf.org/html/draft-ietf-keyprov-dskpp-14

[20] NSA's Cryptographic Message Syntax (CMS) Key Management Attributes, draft-turner-km-attributes-04.txt, April 30 2014
https://tools.ietf.org/html/draft-turner-km-attributes-04

[21] OpenSSL X25519 public key private key generation:

    openssl genpkey -algorithm X25519 -out privkey.pem
  
    openssl pkey -in privkey.pem -pubout -out pubkey.pem
    
[22] OpenSSL list ECC curves

openssl ecparam -list_curves

[23] Acme-tiny - This is a tiny python script that renews Let's Encrypt certificates with openssl, by Ilari Liusvarra.
https://gitlab.com/ilari_l/acme-tiny


