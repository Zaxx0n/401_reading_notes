# PKI

PKI stands for Public Key Infrastructure. It is used for authenticating users.
It works by having a trusted party digitally sign documents.  Afterwards, that key can be used as an identity for the user. 

Devices and users that have keys are often called entities.  Once associated with a key, it can use that key as an identity. A PKI has the purpose of securly associating these keys with entities. 

The signing of keys is done by a Certificate Authority or CA.  The CA has a cryptographic key that it uses for signing these documents, called certificates.  There are many CAs and our web browsers by default trust around a hundred authorities.  

Digital signature technology is essential for the public key infrastructure. From a private key, many public keys can be derived.  A public key can be made available to anyone without losing the secure value of a private key. 
