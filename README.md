# Simex Exchange Protocol Server

A Scala project to implement a server that recieves, and responds with, Simex (Simple Message EXchange) messages.

The aim of this project is to:

1. Write it in Scala for the JVM. 
2. Keep network handshake to the absolute minimum.
3. Use compression to minimise the amount of data transmitted.
4. Use encryption as the only method for communication.
5. Flexibility in the use of privately generated certificates or CA signed certificates.
6. Flexibility in the method of certificate verification.
7. Support [PQC](https://en.wikipedia.org/wiki/Post-quantum_cryptography) to make it secure against future Quantum computer cryptanalytic attack.
