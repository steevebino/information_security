## x)  Read or watch and summarize

## 2.3 One-Way Functions

A One-Way Function (OWF) is a mathematical concept that is relatively easy to 
compute in one direction but significantly difficult to reverse.

**The Concept**: If you have an input $x$, calculating $f(x)$ is simple. However, if you only have the result $y$, 
finding the original $x$ such that $f(x) = y$ is computationally infeasible.

**Trapdoor**: if you possess a specific piece of secret information (the "trapdoor"), reversing the function becomes easy.

**Real-world use**: These are the bedrock of Public-Key Cryptography. Your public key is the one-way function used to encrypt data, 
while your private key is the "trapdoor" that allows you to decrypt it.


## 2.4 One-Way Hash Functions (The "Digital Fingerprint")

While a general one-way function is often used for encryption/decryption, a One-Way Hash Function is designed to produce a 
fixed-length "fingerprint" of a message, regardless of the message's original size.

**Key Characteristics**:

**Fixed Output**: Whether you hash a single word or an entire encyclopedia, 
the output (the hash) is always the same length (e.g., 256 bits).

**Irreversibility**: You cannot reconstruct the original message from the hash.

**Collision Resistance**: It is computationally impossible to find two different 
messages that produce the exact same hash value.

**Avalanche Effect**: A tiny change in the input (like changing a comma to a period)results in a drastically different hash.

**Primary Uses**:

**Integrity**: Ensuring a file hasn't been tampered with during transmission.

**Digital Signatures**: Instead of signing a massive document, you sign the small hash of that document.

**Password Storage**: Storing the hash of a password rather than the plaintext, so even if a database is breached, the actual passwords remain hidden.


## a) Install and test it with a sample hash




