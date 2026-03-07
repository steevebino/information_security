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

**1. Update linux and install Hashcat**

open terminal and install 
<img width="1854" height="1061" alt="Screenshot 2026-03-07 141859" src="https://github.com/user-attachments/assets/675eccc5-d720-4de1-a303-98c799bb8c90" />

verify installation
<img width="1914" height="1076" alt="Screenshot 2026-03-07 142243" src="https://github.com/user-attachments/assets/d8942d40-92a7-4491-abd3-cc49b69afb15" />

check system information (optional)
<img width="1911" height="705" alt="Screenshot 2026-03-07 142420" src="https://github.com/user-attachments/assets/ccfd27fd-7d07-4dbd-95df-5f7699a08f53" />

**2. Install a Wordlist**

Hashcat usually uses a dictionary attack with wordlists.

Install common wordlists:
<img width="1885" height="811" alt="Screenshot 2026-03-07 143955" src="https://github.com/user-attachments/assets/1406bf1b-793b-4815-9a1c-a26a39c1a6ff" />

Create a hash file
<img width="739" height="66" alt="Screenshot 2026-03-07 144139" src="https://github.com/user-attachments/assets/88070600-2ca4-4efa-af88-32d291b4065b" />

and paste this inside,
21232f297a57a5a743894a0e4a801fc3,
and save.

Crack the hash and show the cracked password,
<img width="1877" height="582" alt="Screenshot 2026-03-07 144659" src="https://github.com/user-attachments/assets/51ab591f-4d06-46d5-a997-f39ce7af104d" />

## Crack the hash

update your system
<img width="1857" height="1049" alt="Screenshot 2026-03-07 145628" src="https://github.com/user-attachments/assets/828436d4-48ec-4ab0-8a13-7f3ab12e6878" />

Install John the Ripper

<img width="1558" height="903" alt="Screenshot 2026-03-07 145821" src="https://github.com/user-attachments/assets/6ed44698-b372-4c69-a9f6-35f6bb608eec" />

create a hash file
<img width="1892" height="1053" alt="Screenshot 2026-03-07 150322" src="https://github.com/user-attachments/assets/68f4945b-7285-45ea-8ff7-aa12ae2367f0" />

run a dictionary attack,

sorry i tried the dictionary attack and for some reason, it was not working and I did not get the expected output.





