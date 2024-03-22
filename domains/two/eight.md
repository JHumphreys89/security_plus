---
layout: default
---

[Back to Home](../../index.html) \| [Back to Domain Two](../domain_two.html)

# Subdomain 2.8

_Summarize the basics of cryptographic concepts._

_Terms_: 49

***

#### Digital Signatures

* Uses a mathematical technique to verify the authenticity and integrity of digital messages or documents.
* Involves the use of a private key to sign the hash of a message and a public key to decrypt the hash and verify the message.

#### Key Length

* Refers to the number of bits in an encryption key.
* The longer the key, the more secure the encryption.

#### Key Stretching

* Method used to make weak keys stronger by performing multiple hashes on the key, over and over again.
* Process also referred to as key strengthening.

#### Salting

* Process of adding random data to a password when hashing it.
* This makes it more difficult for attackers to use precomputed tables of hashes to crack passwords.

#### Hashing

* Process of representing data as a short string of text called a message digest or fingerprint.
* A one-way trip, meaning it cannot be reversed.
* Used to verify integrity and confidentiality.

#### Key Exchange

* Process of securely exchanging encryption keys between two parties.
* This process is necessary for secure communication between parties.

#### Elliptic-Curve Cryptography (ECC)

* Asymmetric encryption.
* Instead of numbers, use curves - uses smaller keys than non-ECC asymmetric encryption (perfect for mobile devices).
* Widely used in secure communication protocols such as TLS and SSH.
* Considered more efficient then other public-key crypto methods such as RSA and DSA, and is believed to be more secure against quantum computing attacks.

#### Perfect Forward Secrecy (PFS)

* A property of secure communication protocols that ensures that a session key derived from the long-term key is not compromised even if the long-term key is compromised in the future.
* Is achieved by generating a new session key for each session, which is then discarded after the session ends.

#### Quantum

_Provides security based on the fundamental laws of physics, instead of the mathematical algorithms or computing technology used in classical cryptography._

##### Communications

* Method that uses quantum-mechanical phenomena such as entanglement and superposition to transmit information.
* Believed to be more secure than classical communications because any attempt to intercept or measure the transmitted information would disturb the quantum state of the system, which can be detected by communicating parties.

##### Computing

* Computing paradigm that uses quantum-mechanical phenomena such as superposition and entanglement to perform operations on data.
* Believed to be able to solve certain problems much faster than classical computers, including factoring large numbers and solving discrete logarithm problems, which are the basis of many public-key crypto methods.

#### Post-Quantum

* Field of cryptography that deals with crypto methods that are believed to be secure against quantum computing attacks.
* Methods include lattice-based cryptography, code-based cryptography, hash-based cryptography, and multivariate cryptography.

#### Ephemeral

* Cryptographic keys that are generated for each execution of a key establishment process. These keys are used to establish one or more keys and other keying material in a single key establishment transaction.
* Used to provide forward secrecy (meaning that if an attacker gains access to the long-term private key, they will not be able to decrypt previously intercepted messages.)

#### Modes of Operation

_Procedural rules for a generic block cipher. Different modes of operation result in different properties being achieved, which add to the security of the underlying block cipher. The block cipher processes the data blocks of fixed size in the character._

##### Authenticated

* Provides both confidentiality and authenticity.
* Ensures that data is not only encrypted but also authenticated, meaning that the recipient can verify that the data has not been tampered with during transmission.
* Examples of authenticated encryption modes include Galois/Counter Mode (GCM) and Counter with CBC-MAC (CCM).

##### Unauthenticated

* This mode provides only confidentiality, meaning that the data is encrypted but not authenticated.
* The recipient cannot verify whether the data has been tampered with during transmission.
* Examples include Electronic Codebook (ECB) and Cipher Block Chaining (CBC).

##### Counter

* Mode is a simple counter-based block cipher implementation in cryptography.
* Each time a counter-initiated value is encrypted and given as input to XOR with plaintext or original text, which results in ciphertext block.
* The CTR mode is independent of feedback use and thus can be implemented in parallel in this mode.

#### Blockchain

* A distributed ledger - keep track of transactions.
* Everyone on the blockchain network maintains the ledger - records and replicates to anyone and everyone.
* Holds many practical uses such as payment processing, digital identification, supply chain monitoring, and digital voting.

##### Public Ledgers

* Type of blockchain that is available for general public viewing and verification.
* Maintains participants identities anonymously, their respective cryptocurrency balances, and a record of all the genuine transactions executed between network participants.
* Transactions are allowed and recorded only after suitable verification of the senders liquidity; otherwise, they are discarded.
* Are secure due to their decentralized nature, consensus mechanics, and cryptographic techniques, which make it difficult for malicious actors to manipulate or tamper with the data.

#### Cipher Suites

_Are a combination of encryption, authentication, and message authentication code (MAC) algorithms that are employed with SSL/TLS connections. They are negotiated between the web server and web browser during the initial handshake process._

##### Stream

* Encrypt data as a stream of bits or bytes.
* Utilize a key and a nonce digit to convert the plaintext to ciphertext.
* Both the key and nonce digit create a keystream of pseudorandom bits.
* Finally, we perform the XOR operation between each bit of keystream and plaintext in order to generate the ciphertext.
* Faster than block ciphers when the amount of data is large but it can only facilitate the confidentiality of data.

##### Block

* 

#### Symmetric vs. Asymmetric

* 

#### Lightweight Cryptography

* 

#### Steganography

* 

##### Audio

* 

##### Video

* 

##### Image

* 

#### Homomorphic Encryption

* 

#### Common Use Cases

* 

##### Low Power Devices

* 

##### Low Latency

* 

##### High Resiliency

* 

##### Supporting Confidentiality

* 

##### Supporting Integrity

* 

##### Supporting Obfuscation

* 

##### Supporting Authentication

* 

##### Supporting Non-Repudiation

* 

#### Limitations Regarding Cryptographic Concepts

* 

##### Speed

* 

##### Size

* 

##### Weak Keys

* 

##### Time

* 

##### Longevity

* 

##### Predictability

* 

##### Reuse

* 

##### Entropy

* 

##### Computational Overheads

* 

##### Resource vs. Security Constraints

* 

***

# Demonstrate Your Understanding

[Back to Top](#top) \| [Study in a New Tab](../../resources/study_cards/sub_two_eight.html){:target="_blank"}

_Click or tap on 'Choose a Study Mode' to switch between flash cards, match, learn, test and more._

<iframe src="https://quizlet.com/846873863/flashcards/embed?i=35mna1&x=1jj1" height="500" width="100%" style="border:0"></iframe>