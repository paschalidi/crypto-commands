https://blog.ndpar.com/2017/04/17/p1-p8/
# PKCS #1, PKCS #8, X.509

RFC8017 (PKCS #1 v.2.2)
Defines the traditional format for RSA keys. Two structures:

-----BEGIN RSA PRIVATE KEY-----
RSAPrivateKey
-----END RSA PRIVATE KEY-----

and

-----BEGIN RSA PUBLIC KEY-----
RSAPublicKey
-----END RSA PUBLIC KEY-----

Commands

Generate RSA private key

openssl genrsa -out private.pem 2048
Extract public key from RSA private key

openssl rsa -in private.pem -out public.pem -RSAPublicKey_out
RFC5958 (former PKCS #8, aka .p8)
Defines the format for any private key. Two structures:

-----BEGIN PRIVATE KEY-----
PrivateKeyInfo ::= OneAsymmetricKey
-----END PRIVATE KEY-----

and

-----BEGIN ENCRYPTED PRIVATE KEY-----
EncryptedPrivateKeyInfo
-----END ENCRYPTED PRIVATE KEY-----

The corresponding PEM formats are described in RFC7468 Section 10 and Section 11.

Commands

Convert PKCS #1  PKCS #8

openssl pkcs8 -in private-pkcs1.pem -topk8 -out private-pkcs8.pem -nocrypt
openssl pkcs8 -in private-pkcs1.pem -topk8 -out private-pkcs8-enc.pem
Convert PKCS #8  PKCS #1

openssl rsa -in private-pkcs8.pem -out private-pkcs1.pem
RFC5280 (PKI X.509)
Among other things, defines the format for any public key

-----BEGIN PUBLIC KEY-----
SubjectPublicKeyInfo
-----END PUBLIC KEY-----

The PEM format is described in RFC7468.

Commands

Convert RSA public key between X.509 and PKCS #1 formats

openssl rsa -pubin -in public.pem -RSAPublicKey_out
openssl rsa -RSAPublicKey_in -in pkcs1-public.pem -pubout
Extract public key from RSA private key

openssl rsa -in private.pem -out public.pem -pubout
Extract public key from X.509 CSR

openssl req -in cert.csr -pubkey -noout
Extract public key from X.509 certificate

openssl x509 -in cert.crt -inform pem -pubkey -noout
openssl x509 -in cert.cer -inform der -pubkey -noout
Convert X.509 certificate between DER and PEM formats

openssl x509 -in cert.cer -inform der -out cert.crt -outform pem
openssl x509 -in cert.crt -inform pem -out cert.cer -outform der
