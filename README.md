# node-kmip

KMIP 2.0 is going to be released soon, so the KMIP1.4 specification will be deprecated.

* Create - to create a new managed object such as a symmetric key, and return the identifier.
* Get—to retrieve an object's value given its unique identifier.
* Register—to store an externally generated key value.
* Add Attributes, Get Attributes, and Modify Attributes—to manipulate the attributes of a managed object.
* Locate—to retrieve a list of objects based on a conjunction of predicates.
* Re-Key—to create a new key that can replace an existing key.
* Create Key Pair—create asymmetric keys.
* (Re-)Certify—to certify a certificate.
* Split and Join n of m keys.
* Encrypt, Decrypt, MAC etc. -- cryptographic operations performed on the key management server.
* Export and Import keys to other KMIP servers.
* Operations to implement the NIST key life cycle.
