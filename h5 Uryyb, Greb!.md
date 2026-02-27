## x) Read and summarize

## Applied Cryptography

**Shift to Binary Data** : Unlike classical ciphers that worked on letters of the alphabet, computer algorithms work on bits (0s and 1s). This allows any kind of data—text, images, audio, or video—to be encrypted.

**Complexity and Security** : Computers allow for algorithms that are far too complex to be performed by hand. This complexity is necessary because computers also allow attackers to test millions of possible keys or patterns in seconds.

**Algorithm types** : 

-**Block Ciphers** : These encrypt data in fixed-size chunks (e.g., 64-bit or 128-bit blocks).

-**Stream Ciphers** : These encrypt data one bit or byte at a time, often used for real-time communication.

**Kerckhoffs's Principle**: The section reinforces that the security of a modern algorithm must rest in the secrecy of the key, not the secrecy of the algorithm itself. A "secure" algorithm is one where an attacker knows exactly how it works but still cannot decrypt the message without the key.

**The Power of Automation**: The main advantage of computer algorithms is their efficiency. They can be integrated into hardware and software, making encryption "invisible" to the end-user (e.g., in web browsers or secure file storage).



**Vulnerability to Speed**: The "arms race" in cryptography is driven by Moore's Law. As computers get faster, older algorithms (like DES) become obsolete because they can be "brute-forced" (trying every possible key) in a reasonable amount of time.


