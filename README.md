## Implementation of SHA3 in Python:

The SHA3 family (which includes SHA3-224, SHA3-256, SHA3-384, SHA3-512, SHAKE128, and SHAKE256) is a versatile set of hash functions that can be widely used in key encapsulation mechanisms and Dilithium in post-quantum cryptography (PQC). It belongs to the KECCAK family and utilizes a sponge construction. SHA3 is considered a strong alternative to SHA2 and can be used in many of the same applications.

# Specifications:

Input size: Arbitrary
Block size: 1600 bits
Output size: Depends on the suffix used after the dash. For SHAKES, the output size can be arbitrary.
Number of rounds: 24
