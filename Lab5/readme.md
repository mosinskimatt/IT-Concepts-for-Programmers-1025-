## Matthew Mosinski  Nov 7, 2021

## Executive Summary 
  In the 1950s, during the space race, the world was competing to develop technologies to give the leader in development a competitive edge over the rest of the world. A common issue was that computers were unable to communicate with one another. ARPA (advanced research projects agency) was created after the launch of sputnik and became the center of computing research. This led to the creation of the internet which was originally created by the DOD in order to gain a military and intelligence advantage.
   The internet, interconnected network of networks, was first made available to the government, academies, and research organizations. Each network had an IP address, which devices connected to in order to communicate with each other; however, this was difficult to use. Innovation continued through the 90s and the first browser was released to browse the World Wide Web.
  The 90s was known as the dot com bubble, which created a frenzy of investing and companies gained the ability to sell products online; however, by the new millennium, the bubble burst and many businesses did not survive due to poor business models. Amazon and Ebay are among some of the strongest to survive. The new millennium also birthed Web 2.0, which brought a new era in web development and web surfing. E-mail became the killer app for the internet and drove demand for the internet. 
  As the internet evolved, the United Nations considered access to the internet a basic human right. Users with access to the internet wanted to surf the web faster which brought the growth of broadband. It initially started as a dial-up service with very slow speeds. Research began on ways to increase broadband speed through development of equipment and different ways of delivering internet. The internet became an essential part of commercial and residential communication.
  With the world now connected and information being easily accessible, it was important to develop strategies to keep information secure and to maintain the benefit of the internet for users. The NSA’s job became just this. The information security triad, encryption, firewalls, and many other strategies were developed to assist in keeping the information of businesses and individuals safe.


## Lucidchart
Lucid chart is a useful resource that helps in creating a visualization of the step-by-step process one will endure to reach a desired outcome. It allows the user to analyze all possible outcomes after an input. This is important when creating projects. Having a well thought out plan with inputs and recognizing desired and/or possible outcomes, will help eliminate surprises and/or problems. This helps the process of creating a project go according to plan and meet expectations.

## Introduction to Networking
### Data Transmission
#### Packet:
Unit of data 
#### Packet-Switching:
Technology that allows packets of data to be routed based on destination address 
#### IP Address:
Unique identifying number
#### DNS:
Directory of IP address common names.  For example, 54.239.26.214 might be the IP address of amazon.com
#### Protocol:
Set of rules to allow devices to communicate

The above terms and definitions are related to one another in that they are all essential parts in the data transferring process over the internet. The protocol for device that intends to send a message to another device, is that it breaks down the message into smaller pieces called packets. Each packet has the senders IP Address, the destination IP Address, a sequence number, and a piece of the overall message to be sent. The message gets delivered through packet-switching.

### Networking Hardware
#### Switch vs. Hub
The benefits of a switch over a hub are mainly that a switch is considered intelligent, whereas a hub is not. Hubs and switches both have multiple ethernet ports where multiple devices can be connected. However, if 4 devices are connected to a hub, and device 1 wants to communicate with device 2, devices 3 and 4 will also receive the data that device 1 was attempting to send to only device 2. This wastes bandwidth and could be a security/privacy concern. A switch stores the mac addresses with a corresponding port of connected devices, therefore, only sends incoming data back out to devices it was intended for. Switches reduce unnecessary traffic on the network.

#### Router vs. Switch and Hub
Routers are preferred over hubs and switches because routers have the capabilities of reading IP Address. Hubs and switches only communicated over and LAN with mac addresses. A router forward data from one network to another. When data comes into a router, the router determines if the data was meant for its own network or another network. If it was meant for its own network, then the router accepts and processes the data.  If the router is not meant for its own network, it sends the data off to another network (packet-switching).

### Network Topologies
#### Single point of Failure
A network topology is the manner in which a network is configure in terms of devices and their relation to the main point of connection so that they can communicate internally and externally. There are multiple network topologies, and it is important to have the right one to ensure reliable connections, even through failures. Single point failure is the worst of the failures in terms of network topologies. This is where there is a single point of connection, for example an in-home router, and when the single point of connection if lost, all devices lose connection too. This is relevant in the star and ring connection topologies, which is why the star and ring topologies are perhaps the most unfavorable topology type.

#### Infrastrucutre vs. Wireless Mesh
Infrastructure topology is perhaps the most common. It is a single connection of a modem and router that delivers a wireless signal to devices that wish to connect to the internet. Problems with this topology is seen in larger building where the further you get from the router, the worse the connection is because it is relied on the capability of one router. This is where a mesh connection is beneficial. A mesh connection has multiple access points, wired to the router for a more reliable, larger area of wireless connection. The mesh connection is more favorable, however, both connection types still have potential for single point failure in that if the router or modem lose connection, so do the connected access points and devices.

### Network Design
My attached network design portrays a typical infrastructure topology connection that begins at the source, the internet. The internet cable/dsl internet is received by the modem and transferred to internet. The internet is then received by the routers, one being a wireless router, and one being a wired router (it is possible to have a modem/router in one device). The wired router, on the left side of the diagram, has a computer connected to it which, depending on the router/modem, most likely has the strongest connection because the connection is wired. The other router/gateway is wireless. This wireless connection is delivered to a computer and a printer. This wireless connection allows for the printer to communicate with the computer through the router.

### NSA/CSS
The NSA is a security agency, that oversees other agencies, that take responsibility for the security of the United States’ network connections. NSA Cybersecurity prevents and eradicates threats to U.S. national security systems with a focus on the Defense Industrial Base and the improvement of U.S. weapons' security. They operate on four pillars of focus, with the first being honesty. The NSA recognizes that the US and its citizen have placed a great trust in them and honor the public’s need for openness. The second pillar is respect for the law and adhering to the constitution. The third pillar is Integrity. The NSA vows to operate in a manner in which there is an understanding that they work for the American people, will apply good judgment in the best interest of the American people. The fourth and last pillar is transparency. The NSA ensures that each activity they are involved in ensures the safety security, and liberty of American Citizens.

## Cybersecurity and Encryption
### Information Systems Security
#### Security Triad
Applying the concepts of the security triad to amazon’s online chat that it maintains the confidentiality element of the security triad. Amazon customers entrust amazon to keep the chats confidential and restricts access to only those that should see it, on a need to know bases. Amazon maintains its integrity throughout the chat by aiming to accurately address the topic of conversation and not alter any information. Lastly, is availability and amazons chat is available 24/7, and the information inside of the chat is only available to those authorized to the information. 

#### Authentication
3 daily tasks that require authentication
One daily tasks requiring authentication is, opening your cell phone. Cell phones require a password to log into it, whether it be a biometric password, a pin, a phrase, or a combination of several authentication methods. Let’s assume the cell phone is in a safe location where only those authorized could access it. This would be an example of multi-factor authentication.
Another daily authentication task I experience is, opening my email. My email requires one to open their cell phone or computer and enter a password to view the messages, presumably meant for the owner of the device. This could be converted to multi-factor authentication by enabling two step verification method to ensure access to only those authorized.
Something as simple as logging into one’s computer to do schoolwork requires authentication by having to put in a password to log into the university page.  This becomes multi-step authentication when the computer is password protected as well because now it takes two passwords to do the schoolwork. One password for authorized users to access the computer, and then another password to enter the university homepage of the student. But just because one is authorized to uses the computer, does not make that individual authorized to log into the student’s university home page.
Two step verification/multi-factor authentication is growing as security protocols evolve. Passwords are required to be more complex, and many websites have CAPCHAS in order to log in and/or create an account. This is sometimes for the security of the website and not the user. 

#### ACL and RBAC
ACL- Access Control List – Access control occurs after authentication and determines what rights the user has within. For example, for this course, students were required to add Professor Harrison as a collaborator, giving her abilities to access and modify information within the student’s github. The pros to ACLs is that each person is considered and permissions are assigned to individuals specifically. The drawbacks to that is, as the organization grows, it becomes difficult sifting through the people and selected one by one what the individual does or doesn’t have access to. 
RBAS- Role Based Access Control – Role based access control is simply another filter that one has to go through to ensure access. In this form of access control, users are assigned to a role and the role is what determines what individuals have access to. For instance, there could be one administrator who has complete control over the information. The one administrator full control over the information, whereas a reader/user only could view the information. This method is more organized and less specific that the ACL access method because permissions are granted based on roles. The cons of the RBAS method is that it is less customizable.

#### Ciphertext, Public Key and Private Key
When one wants to transmit data and ensure the information only gets to the person that it was intend for, they will place an encryption on the information. Encrypted information requires to keys. The sender will have a public key, and the recipient will have a private key. The public keys can be obtained by anyone who would like to send an encrypted message. The private is used to unlock the message. The best example would be a locked mailbox. Anyone (public key) can send a message, but only the recipient (private key), can decode and read the messages. While the text is locked it is considered to be ciphertext, which is simply numbers and symbols that are scrambled in order to hide what the actual message is saying until the private key holder receives it.

#### Public Key Cryptography
Public key encryption is important in ensuring confidentiality. Those who encrypt messages only want the sender and recipient to view the message. Therefore, they secretly send bits of information to one another so that only the keyholders can decrypt the message. This is important for things such as banking.

### Cryptography
#### Encryption
After inputting cryptography is a growing field in Caesars Cipher Exploration and turning the lock, my encrypted message was “kzgxbwozixg qa i ozweqvo nqmtl.” In this encryption, the letter moved 9 down the alphabet 9 spaces. Therefore, the first letter of the alphabet, “a,” now becomes the ninth letter of the alphabet, “i.”

#### Frequency Fingerprint
The frequency fingerprint cipher shows the frequency that letters appear in the English language. After typing the phrase “cryptology is a growing field” in the Frequency Fingerprint Exploration, it is discovered that the letter vowels are the most common letters used in the English language. I also input the encrypted message from the previous example, “kzgxbwozixg qa i ozweqvo nqmtl,” and it was discovered the letters moved laterally nine spaces. This would be different if we used different languages as some languages have different alphabets, therefore both the sender and receiver would have the know language of the message that was being sent.

#### Polyalphabetic Cipher
The polyalphabetic cipher is when the sender and recipient agree on a code word. The code word is broken down into numbers based on the letters within the words position in the alphabet. Ex. A=1, B=2 Y=25, Z=26. The numbers are then places in a repeating pattern through the message to encrypt and decrypt the message. This method flattens the letter frequency and gives the message higher security, making it more difficult to interceptors to decrypt.

#### Polyalphabetic Example
I continued the same phrase “cryptography is a growing field” for this example and choose the code word “chair.” The encryption result was “fzzlrosjhkg jb s jzpfaqo grwol,” much different than the encryption from the previous examples. The fingerprint frequency was flattened and make the code much more difficult to decrypt

#### Brute-Force
A Brute-Force attack tries every possible decryption key for a cipher. Brute-Force’s effectiveness renders the Caesar method for encryption unreliable. The code for a Brute-Force attack is relatively simple. The encrypted message is entered, and the code is written so that each letter of the alphabet and corresponding number are applied to the message. The output will be many lines of code, however the one that is written in plain English.

## Conclusion
The evolution of the internet has connected the world and has become a commodity that almost everyone around the world now has access to. However, it is important to “lock your doors” to protect and ensure that information is only accessible to those the information should be accessible to. The importance of security and encryption. Lacking in these areas could result in unfavorable consequences such as CWEs.

