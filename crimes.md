# Crimes in computing

## Hackers
- In the early days of computing (1960's to the early 1970's, a "hacker" was a **creative programmer who wrote very elegant or clever programs**

Skilful programmers, usually refered to as intruders or hackers, can gain unauthorised access, or break-in, to computers and computer networks. Hackers can either act directly, by penetrating the system themselves, or indirectly, by embedding a destructive program within the system that causes serious damage or problems to the machine.

- The Oxford Dictionary of Computing defines:
  + **hacking** ==> ‘unauthorised access to computer material’
  + **hacker** ==> ‘a person who attempts to breach the security of a computer system by access from a remote point, especially by guessing or otherwise obtaining a password’

### Ethical hacker
- Help the organization take preemptive measures against malicious attacks by attacking the system himself.
- All the while staying within legal limits.
- [Certified Ethical Hacker (CEH)](https://en.wikipedia.org/wiki/Certified_Ethical_Hacker)
- http://www.eccouncil.org/Certification/certified-ethical-hacker

### Blackhat Hacker (cracker)
-  An individual with extensive computer knowledge whose purpose is to breach or bypass internet security.
-  Also known as crackers or dark-side hackers.
-  The general view is that, while hackers build things, crackers break things.

### White hat (computer security)
- An ethical computer hacker, or a computer security expert, who specializes in penetration testing and in other testing methodologies to ensure the security of an organization's information systems.

### Hacktivism or Political hacking
- The act of hacking, or breaking into a computer system, **for a politically or socially motivated purpose**.
- the use of hacking to promote a political cause
- The individual who performs an act of hacktivism is said to be a hacktivist.

The use of hacking for political purposes such as promoting a political cause or spreading anti-war messages via the Web.  Hacktivism is the use of hacking to promote a political cause.

A distinction must be made between modern and old hackers. Where early hackers were gifted individuals who exercised their technical skills for self-esteem, intellectual From a historical viewpoint, Sara Baase observes three phases of hacking:
firstly, the early years (1950s and 1960s),
secondly, the middle period (1970s to the 1990s), and
thirdly, the latest period (beginning of the 1990s). In the first phase, hacking had a positive connotation, whereas in the second it had a negative meaning. In the third phase, hacking is introduced to the Internet and cyberspace.
Most popular hacking techniques
Piggybacking:
The hacker invades a computer system by pretending to be a legitimate user of the network. The hacker uses the user’s identification and password and logs into the network illegally.

### Cracker
- The term cracker was invented by hackers to defend their reputation. Whereas the term hacker does not always have a negative connotation and it can equally refer just to a skilful programmer who is obsessive about programming, the term cracker always has a negative meaning, and it is associated with a person who gains unauthorised access to a computer system for malicious purposes.
- A hacker is ‘a person who had an instinctive knowledge enabling him or her to develop software apparently by trial and error’. In fact, based on the intentions of the computer intruder, there is a fundamental distinction between the two different personas: the hacker and the cracker.

### PHREAKING
- Another form of hacking is that of phreaking. Phreaking is a synthesis of the words ‘phone’, ‘free’, and ‘freak’ and is used to describe illegal access to telephone services and use of these services to satisfy the individual goals of the phreak.

### Scavenging
- The hacker searches through stray data for clues that might unlock the secrets of a targeted computer system. A similar technique is known as dumpster diving, wherein the hacker searches electronic garbage in order to find discarded documentation that may include user names and passwords

### [Aaron Swartz](https://en.wikipedia.org/wiki/Aaron_Swartz)
    +  an American computer programmer, entrepreneur, writer, political organizer and Internet hacktivist.
    +  involved in the development of the web feed format RSS and the Markdown publishing format, the organization Creative Commons, the website framework web.py and the social news site, Reddit, in which he became a partner after its merger with his company, Infogami.

===

## [Denial of Service Attack (DOS)](https://en.wikipedia.org/wiki/Denial-of-service_attack)

- An attempt to make a machine or network resource unavailable to its intended users, such as to temporarily or indefinitely interrupt or suspend services of a host connected to the Internet.
- The flood of incoming messages to the target system essentially forces it to shut down, thereby denying service to the system to legitimate users.
- An intentional action designed to prevent legitimate users from making use of a computer service.

### [Syn attack](https://en.wikipedia.org/wiki/SYN_flood)
- A SYN flood is a form of denial-of-service attack in which an attacker sends a succession of SYN requests to a target's system in an attempt to consume enough server resources to make the system unresponsive to legitimate traffic.
- [Three-way handshake](https://en.wikipedia.org/wiki/Transmission_Control_Protocol#Connection_establishment)
    1. The client requests a connection by sending a `SYN` (synchronize) message to the server.
    2. The server acknowledges this request by sending `SYN-ACK` back to the client.
    3. The client responds with an `ACK`, and the connection is established.

===

## [Malware](https://en.wikipedia.org/wiki/Malware)

- [What Is the Difference: Viruses, Worms, Trojans, and Bots?](http://www.cisco.com/c/en/us/about/security-center/virus-differences.html#5)

### Rootkit
- A collection of computer software typically malicious.
- Designed to enable access to a computer or areas of its software that would not otherwise be allowed (for example, to an unauthorized user) while at the same time masking its existence or the existence of other software.
- A piece of software that allows an unauthorized user to override security and get administrator access to a computer.

### Virus
- A small program written to alter the way a computer operates, without the permission or knowledge of the user.
- A virus must meet two criteria:
    1. It must **execute itself**. It will often place its own code in the path of execution of another program.
    2. It must **replicate itself**. For example, it may replace other executable files with a copy of the virus infected file. Viruses can infect desktop computers and network servers alike.
- A piece of self-replicating code embedded within another program (the host).
- A self-replicating program reproduced by attaching executable copies of itself to other.
- Cannot run independently. Initially, the virus requires a host program to infect, and it is not executed until the host program is run.
- Can spread rapidly through hosts that share the same infected programs or disks that include these programs.
- Very difficult for the common user to detect.
- Most viruses use sophisticated techniques both to infect the system and to avoid detection.
- The most common type of viruses:
  + (1) boot sector viruses: infects the system boot and spreads whenever the system is loaded;
  + (2) e-mail viruses: spread through e-mail attachments; and
  + (3) macro viruses: spread through documents that contain macros—programming instructions that perform automated tasks.

### Worm
- Programs that replicate themselves from system to system without the use of a host file.
- Although worms generally exist inside of other files, often Word or Excel documents, there is a difference between how worms and viruses use the host file.
- Self-contained program that spreads through a computer network by exploiting security holes in the computers connected to the network.

A worm is a virus-like program that makes copies of itself across network connections, seeking uninfected workstations in which to reproduce. In contrast to a computer virus, a worm program can travel independently through different hosts and resides more in the computer memory of a system rather than on disk. The aim of a typical worm is through continued reproductions to cause disk or memory overload throughout the network. Inevitably, the network freezes and the system has to be reloaded; this process causes complete loss of memory data that have not been saved on disk. On the other hand, the consequences of a worm are not as destructive as that of a virus. A worm is a memory virus; thus it can be removed by shutting down the infected system.


### Trojan Horse
- Files that claim to be something desirable but, in fact, are malicious.
- Do not replicate themselves, as viruses do.
- Contain malicious code, that, when triggered, cause loss, or even theft, of data.
- A program with a benign capability that conceals another, sinister purpose. When executed the program performs the expected task along with an unknown negative task.
- A destructive program disguised to appear as something benign.
- The conditions of activation are determined by the computer programmer who designed the program.
- Usually posted through the Internet disguised as a harmless program, game, or utility.
- Used to exchange secret information between hackers.
- Release other malicious programs such as viruses or worms.

===

## Others

### [zero-day (or zero-hour or day zero) attack or threat](https://en.wikipedia.org/wiki/Zero-day_(computing))
- an attack that exploits a previously unidentified vulnerability

### Cyberbullies
- someone who uses the Internet to harass a particular target, usually one known in everyday life, often using fake identities or public Web sites to enable the harassment

### Crowdsourcing
- An online method to get information or ideas from a large group of people

### Embedded System
- A computer used as a component of a larger system

### Bot network
- According to some estimates, 90 percent of spam is distributed through bot networks.

### [(Anonymous) remailer](https://en.wikipedia.org/wiki/Anonymous_remailer)
- A server that receives messages with embedded instructions on where to send them next, and that forwards them without revealing where they originally came from.
- Can provide a virtually untraceable level of anonymity to email messages.
- Internet users who do not want to reveal their identity can send email to a remailer service, which uses a computer program to strip the originating IP number or header from the message.

### Password guessing

Guessing the password may involve various techniques, such as dictionary attacks (searching with a dictionary file for words fitting to the password); hybrid attacks (adding numbers or symbols to the filename to successfully guess the password); brute force attacks (long-time guessing a password).

### Computer Sabotage

Computer sabotage is one of the most dangerous forms of computer crime. The computer saboteurs create tiny but destructive programs that cause serious hardware and/or software problems in a computer system, such as deleting files in the hard disk, destabilising the computer system, clogging up mail servers by sending fake e-mails to the address found in the address book of the victim, and stealing information from the computer of the victim and sending this information back to the saboteur. There are different kinds of these malicious programs; the most popular are worms, viruses, bacteria, Trojan horses, logic bombs, time bombs, and spywares. As can be seen, the terminology of these programs is biological or military. This is not without purpose. Some of these programs such as the viruses and bacteria mimic in programmable form the behaviour of the living organisms after which they are named; others bring the destructive consequences of the war weapons which they represent electronically.

### Logic Bombs and Time Bombs

Logic Bombs and Time Bombs are kinds of Trojan horses. A Logic Bomb inserts secretly into a system and causes a destructive action when a certain logical event or a sequence of events happens (e.g., if program x runs, then do destructive action y). Similarly, a Time Bomb is triggered after a particular time-related event (e.g., if program x runs after date y, then do the destructive action z). Frequently, a logic bomb or a time bomb is an act of vengeance. For example, a programmer who is unfairly removed from his or her post may plant a time bomb to be triggered after the date of his or her removal.

### Spyware

A spyware is a type of surveillance program that is inserted into a computer system in order to monitor, store, and analyse the electronic transmissions of the system. A spyware is not itself a destructive program. In some cases, spywares are used for security reasons. However, it must be mentioned that the risk of infection is increased if the user opens e-mail attachments from unknown senders, downloads unauthorised software, uses discs from different computers, and does not follow regular security measures. The user can be alerted to the presence of a destructive program by annoying messages on the screen, strange behaviour of the system, problems in system performance, or partial destruction of data. In this case, the user is recommended to use a vaccine or disinfectant utility (also called an anti-virus utility) that searches for malicious programs throughout the system, informs the user about possible infections, and usually cleans the infected files from the destructive code. The user is also able to select a safeguard option of the program that protects the system from unexpected virus attacks on-line. This option helps the user monitor all suspicious virus-like activities. Most anti-virus programs download new updates on-line as new viruses appear. Thus, in order to be effective, an anti-virus program must be frequently updated with the new virus-fighting database and, if there is network, must be installed in all network nodes.

Alongside the anti-virus programs some additional actions are suggested in order to minimise the risks of infection:

1. Make sure all purchased software comes in sealed, tamper-proof packages.
2. Be careful about software received from friends, as well as files downloaded from bulletin boards, the Web, e-mail attachments, and other forms of shareware and freeware programs.
3. Be particularly careful with software of unknown origin.
4. Avoid using disks from the office computer at the home computer and vice versa.
5. Make backup copies of software and data. With regard to making backups, it is important that the user follows a systematic procedure of backups and security. This procedure is known as good practice and includes: (1) regular file saves while working; (2) frequent backups of computer data; and (3) system protection. Good practice aims to improve the security of the computer system and protect programs and data in case of destructions, misuses, and malfunctions. The backup copies must be kept in different versions by following a historical timeline. If a recent version is corrupted, the user must be able to retrieve data from an earlier version. Once backup copies have been made, they should also be protected and stored in a secure location away from the originals.

Moreover, in 1990, the British Parliament passed the Computer Misuse Act (CMA). CMA divides computer misuse offences into three categories:
1. Unauthorised access to computer material
2. Unauthorised access with intent to commit or facilitate commission of further offences
3. Unauthorised modification of computer material
