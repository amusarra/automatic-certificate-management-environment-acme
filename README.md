# How to request and install an SSL certificate on Apache Karaf
In this repository you can find all the certificates used in my post published on the blog [Antonio Musarra's Blog](https://goo.gl/BVpbWo).

In detail:

* __api.dontesta.it.key.pem__: A RSA (2048 bit) private key pair
* __api.dontesta.it.csr.pem__: Certificate Signing Request (CSR)
* __api.dontesta.it.cer.pem__: Certificate issue by Let’s Encrypt CA
* __api.dontesta.it.cer.bundle.pem__: Bundle Certificate with Certificate Chain
* __ca.cer.pem__: Certificate of the Certificate Authority (Let’s Encrypt)
* __api.dontesta.it.pfx__: Certificate + KeyPair in PKCS#12 format
* __dontesta-karaf-server.jks__: Java Keystore created from PKCS#12
