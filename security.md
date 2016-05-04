# Network securty

## Security Injections

- [Real life examples](http://cis1.towson.edu/~cssecinj/links-resources/real-life-examples/)
- [Covert channel](https://en.wikipedia.org/wiki/Covert_channel)
    +  a type of computer security attack that creates a capability to transfer information objects between processes that are not supposed to be allowed to communicate by the computer security policy.

### Resources

- [SANS - Reading Room](https://www.sans.org/reading-room/categories)
    + the most trusted and by far the largest source for information security training in the world.
- [System Administrator - Security Best Practices](https://www.sans.org/reading-room/whitepapers/bestprac/system-administrator-security-practices-657)
- [Spoofing: An Overview of Some the Current Spoofing
Threats](https://www.sans.org/reading-room/whitepapers/threats/spoofing-overview-current-spoofing-threats-321)
- [List of TCP and UDP port numbers](https://en.wikipedia.org/wiki/List_of_TCP_and_UDP_port_numbers)
- [Firewall](https://en.wikipedia.org/wiki/Firewall_(computing))
    + A network security system that monitors and controls the incoming and outgoing network traffic based on predetermined security rules.
    + Typically establishes a barrier between a trusted, secure internal network and another outside network, such as the Internet, that is assumed to not be secure or trusted.
    + A set of rules that is configured by the security guys.
        * `allow all` vs `deny all`

---

## [Denial-of-service attack](https://en.wikipedia.org/wiki/Denial-of-service_attack)
- An attempt to make a machine or network resource unavailable to its intended users, such as to temporarily or indefinitely interrupt or suspend services of a host connected to the Internet.
- The flood of incoming messages to the target system essentially forces it to shut down, thereby denying service to the system to legitimate users.

---

## [Syn attack](https://en.wikipedia.org/wiki/SYN_flood)
- A SYN flood is a form of denial-of-service attack in which an attacker sends a succession of SYN requests to a target's system in an attempt to consume enough server resources to make the system unresponsive to legitimate traffic.
- [Three-way handshake](https://en.wikipedia.org/wiki/Transmission_Control_Protocol#Connection_establishment)
    1. The client requests a connection by sending a `SYN` (synchronize) message to the server.
    2. The server acknowledges this request by sending `SYN-ACK` back to the client.
    3. The client responds with an `ACK`, and the connection is established.

---

## [Check digit](https://en.wikipedia.org/wiki/Check_digit)

---

## Cryptography

- Plain text ---> cipher text
- encode and decode
- only authorized party can read

**Encryption** is the process of encoding a message so that its meaning is not obvious; **decryption** is the reverse process, transforming an encrypted message back into its normal, original form.

Alternatively, the terms encode and decode or encipher and decipher are used instead of encrypt and decrypt.  That is, we say that we encode, encrypt, or encipher the original message to hide its meaning. Then, we decode, decrypt, or decipher it to reveal the original message. A system for encryption and decryption is called a cryptosystem.

The original form of a message is known as plaintext, and the encrypted form is called ciphertext.

### Resources
- [Alice and Bob](https://en.wikipedia.org/wiki/Alice_and_Bob)
- [Public-key cryptography](https://en.wikipedia.org/wiki/Public-key_cryptography)
- [Pretty Good Privacy (PGP)](https://en.wikipedia.org/wiki/Pretty_Good_Privacy)
- [MIT PGP Public Key Server](http://pgp.mit.edu/)
- [Secure Shell, or SSH](https://en.wikipedia.org/wiki/Secure_Shell)
- [Encrypting File System (EFS)](https://en.wikipedia.org/wiki/Encrypting_File_System)
- [Digital signature](https://en.wikipedia.org/wiki/Digital_signature)
    + [Non-repudiation](https://en.wikipedia.org/wiki/Digital_signature#Non-repudiation)
    + Asymmetrical
- [Cryptographic hash function](https://en.wikipedia.org/wiki/Cryptographic_hash_function)
    + One-way operating, cannot be reverse-engineered

![](https://upload.wikimedia.org/wikipedia/commons/thumb/f/f9/Public_key_encryption.svg/375px-Public_key_encryption.svg.png)

---

### Web filter
-  a program that can screen an incoming Web page to determine whether some or all of it should not be displayed to the user.

### Firewall
- computer, positioned between a local network and the Internet, that monitors the packets flowing in and out.
