# Simex Exchange Protocol Server

A Scala project to implement a server that recieves, and responds with, Simex (Simple Message EXchange) messages.

The aim of this project is to:

1. Write it in Scala for the JVM. 
2. Keep network handshake to the absolute minimum.
3. Use encryption as the only method for communication.
4. Enable the use of privately generated public-private keys in addition to ones from certificate authorities.
5. Enable end users to use bespoke methods for certificate verification.
6. Support [PQC](https://en.wikipedia.org/wiki/Post-quantum_cryptography) to make it secure against Quantum computer cryptanalytic attack.
