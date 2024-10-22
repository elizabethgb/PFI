# PFI

Engineering final project - research study: Lightweight Cryptography Study
Asymmetric cryptography algorithm survey and implementation comparison in efficiency

## Abstract

Cryptography is as old as communication. At all times, people sought to communicate privately without a third-party intruder being able to decipher the content. Over time, the communication channel evolved, and with it the means of securing data.

Today is no exception and the open nature of the internet made their protection more complex, generating a great privacy problem; that was intensified with the boom of small interconnected intelligent devices (such as *IoT* or *WSN*), which take data from the environment and share it over the network, thus generating more and more data (arising of *Big Data*), which must be secured.

The main drawback of these devices is their low computing power, which requires light adaptations of cryptographic methods, and to determine acceptable levels of security, which cover what is called *Lightweight Cryptography*.

The present work, named **"Comparative Study of Lightweight Cryptography Algorithms"**, was carried out according to an incremental iterative method. In this, the mathematical bases and the different known algorithms were deepened, selecting the *Asymmetric Lightweight Cryptography* as the scope to study. Subsequently, *lightweight implementations* were made, with mathematical contraptions that improve computing efficiency, and then comparisons between them were formulated. The seen algorithms are: *Light RSA*, *D-Rabin* (which was discarded because it was not considered an encryption method), *Elliptic Curve Diffie-Hellman* and *Elliptic Curve ElGamal*.

Finally, it was concluded that, with the same level of security required, the solutions with *elliptic curves* turn out to be the most efficient in computing power. As a good practice, it is recommended to evaluate ad-hoc solutions, always prioritizing the particularities of each case, and the estimation of the required security level should be considered, so choices and decisions should be based on them. Also, it is encouraged to raise awareness of the need to safeguard data and promote practices that prioritize that.

**Keywords**: Cryptography; IoT; WSN; Lightweight Cryptography; Comparative Study; Efficiency; Asymmetric Lightweight Cryptography; RSA; Rabin; DHKE; ElGamal; ECC; ECDH; ECEG.

## Built With

- Python 3