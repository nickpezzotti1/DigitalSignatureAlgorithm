# DigitalSignatureAlgorithm
A DSS algorithm written in python. Allows to sign and verify messages. Following the DSS (digital signature standard), and adopting mathematically notions in the SHA algorithms with 4096-bit keys. The keys are hard-coded because intended for a service. Using the following Openssl command propmt command the keys can be substituted:

openssl rsa -in private.pem -text -noout

Digital signatures (legally binding in many countries) allow a message to be signed by the sender (or whomever holds the private key) and verified by anyone with the respective public key.
