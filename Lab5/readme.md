Executive Summary

This lab taught us to realize the importance of network hardware, software, topology, and security.  

Lucidchart
My experience with Lucidchart was pleasant.  When I was in graduate school, we had to do several projects with Access.  I didn't have any resources like these websites to guide me. (They probably existed, but I didn't know I should look for them)  I only had a textbook and the teacher.  The teacher was TERRIBLE!  He refused to answer any questions (in class or during office hours).  He felt that graduate students should be able to teach themselves, which is a ridiculous theory!!!  In the end, my experience with flowcharts was so terrible that I have avoided them for years.  Now, using Lucidchart, I was pleasantly surprised with the results. 

Introduction to Networking

Data Transmission

Protocol          - 1. Set of rules to allow devices to communicate 
Packet            - 2. Unit of data 
IP Address        - 3. Unique identifying number 
Packet Switching  - 4. Technology that allows packets of data to be routed based on destination address 
DNS               - 5. Directory of IP address common names.  For example 54.239.26.214 might be the IP address of amazon.com


Network Hardware

Both the Hub and the Switch are internal (LAN) devices that connect to the ethernet with multiple portals.  But, the Switch is 'intelligent', which means that it learn IP addresses & save it.  With this data detected & saved, the Switch can send packets only to specific ports.  This increases security and reduces unnecessary traffic (bandwidth) on a network.  

There are several benefits to a Router over a Hub or a Switch.  First, a Router can reach other reach outside of the LAN.  A Router often has a Switch inside of it and it can connect to other Switches.  The Router can read IP addresses and, with this information, determine which packets to bring into its network towards its devices versus allowing some packets to move on undisturbed.  A router is a 'Gateway' to the internet.  

"The Hub & Switch are used to create networks, but the Router is used to Connect to Networks" - Narator from video

Network Topologies

A 'Single Point of Failure' is a an event where a computer or system of computers loses internet connection.  Generally, it is caused by a poor design with the internet distribution.  Star, Ring, and Bus topologies can all suffer from SPOF.  With a Star topology, the SPOF happens when the Hub or Switch fail.  With Ring or Bus topologies, an SPOF can happen if one or more computers in the system crash / are disconnected.  The Ring and Bus topologies have this built-in error because their design causes one computer to rely on the next. 

Infrastructure topology is very similar to Star topology, but it includes wired & wireless technology.  Wireless Mesh topology is similar to Mesh Topology, but it includes wireless capabilities.  I believe the Wireless Mesh Topology is the better system because it allows for wired & wireless connection while creating several redundancies for connection points. 

Network Design
The design for my network is simple.  The Internet comes from a tower to a modem.  From the modem, the internet travels to a router.  The router projects the internet to a cloud.  The cloud provides internet to the 2 PC's and the printer.  Then, the 2 PC's connect to the printer. 

NSA/CSS
The NSA's role in cybersecurity is pretty vast.  The NSA prevents drug smuggling, illegal immigration, attacks from terrorist groups, identity theft, and illegal commerce.  Because of the internet, these crimes of identity theft, sex trafficking, terrorist group communication have become increasingly easy.  The NSA's job is to try to intercept these communications and try to prevent or stop crimes from happening.  

Cybersecurity and Encryption
Imagining that I am part Amazon.com online chat, I envision that Confidentiality, Integrity, and Availability would all affect my job.  Availability is obvious because people worldwide want to be able to find help at all times of the day every day.  So, speaking to someone in Cleveland, Ohio at 6pm means that you could be talking to someone in the Phillipines at 6 am, which happened to me this week.  Confidentiality would be part of the conversation because I would have to make sure the person on the other line is the customer that he/she says he/she is.  It would be easy to using phishing and/or pretexting schemes to gain access to the account if confidentiality is not effective.  Integrity is integral to all companies because it is important to make sure that all data for customer and for sales are up-to-date, truthful, and precise. 

Three daily tasks that require authentication are logging into your work PC, paying bills, and looking at your facebook account.  For logging into a work PC, this task could be changed to becoming a multi-factor authentication by adding a tool to the login, such as an RSA SecurIDToken.  (I used to have something similar to this when I worked at Diebold).  For paying a bill, a security question could be added to the login process in addition to the password. For looking at your FaceBook account, a text can be sent to the phone number on the account to verify the appropriate user. 

ACL is a form of Access Control that is easily understood.  It is a process where permissions are given to each user by an administrator.  It is simple, but time-consuming.  Also, management of this system becomes increasingly difficult as the size of the system grows.  RBAD is a form of Access Control that is more complicated to set up than ACL, but easier to maintain as the system grows.  Instead of an administrator assigning a person permissions like ACL, RABC gives each person a role and the role then receives access. 

Ciphertext is when a data is encrypted before it is transmitted and then decrypted once it is received.  This system only works when both parties have a 'Symmetric Key Encryption'.  Public Key Encryption requires a public key and a private key.  A message has to be encrypted before it is sent using a Public Key.  Once it is received, the one who receives it can use a 'Private Key' to decrypt it.  
, and a Private key

We need public Key Cryptography in order to communicate safely on the internet with sources that we have not yet met (or agreed upon symmetric key encryption with them). 

Cryptography

"Cryptopgraphy is a growing field" = "Fubswrsjudskb lv d jurzlqj ilhog."  I used the Ceasar Cipher for this. 
In the 'Frequency Fingerprint Exploration' box, I typed "My dog's name is Boris and he's cute!"  The result is what most people would expect. 

A Polyalphabethic Cipher is similar to a Ceasar Cipher, but it has added layers.  Instead of a single shift, there are layers of shifts that are based on a single word.  Using this technique, the code flattens the Frequency Fingerprint.  
I typed "My dog's name is Boris and he's cute!" and I used 'Boris' as the Shift Word.  
The result gibberish and a very flat fingerprint frequency. 

Brute-Force
Brute-Force is a form of decryption where a hacker just tries all possible keys to try to decipher a code.  It relates to Kerckhoff's principle in that Kerckhoff suggests that encryption should not matter as much as the secrecy of the message. 
