# Table of contents

- Schneier 2015: Applied Cryptography: Chapter 1: Foundations
- Frequency Distribution of letters for French
- Choose a password manager
- ETAOIN
- Demonstrate the use of a password manager: LastPass
- Encrypt and decrypt a message + Bonus: send and receive encrypted message over email
- Sources and links

# Schneier 2015: Applied Cryptography: Chapter 1: Foundations

> https://learning.oreilly.com/library/view/applied-cryptography-protocols/9781119096726/08_chap01.html#chap01-sec006

1. Cryptography is like a secret language that helps people talk securely over the internet. This means sending coded messages and decoding them on the other end.
2. Cryptography has three main goals: 
   - authentication: making sure the message came from the right person
   - integrity: making sure the message wasn't changed along the way 
   - nonrepudiation: making it impossible for someone to deny sending a message
3. Symmetric algorithm: some secret codes use the same key to lock and unlock the message.
4. Asymmetric algorithm: other secret codes use two keys: one to lock and a different one to unlock.
5. Cryptanalysis is like solving secret codes without knowing the secret key. 
6. There are different ways to attack secret codes:
   - ciphertext-only:  trying to crack them with only the coded message
   - known-plaintext: if you know part of the message 
   - chosen-plaintext: if you can choose parts of the message 
7. One-time pads are really secure because they use a completely random key that's as long as the message. It's like having a unique, one-time-use key for every message.
8. Attacks on secret codes are like solving puzzles. Some are easy, and some are hard.
9. Steganography is like hiding a secret message inside another message. 
10. Substitution and transposition ciphers are like old-school secret codes. Substitution swaps letters, like changing A to Z. Transposition rearranges letters.
11. XOR encryption is very basic and easy to use, but it's not very safe.

# Frequency Distribution of letters for French

> https://fr.wikipedia.org/wiki/Fr%C3%A9quence_d%27apparition_des_lettres

```
Here are the six most common letters in the French language based on their frequency of use:
```

<img width="169" alt="image" src="https://github.com/piafernandez/h4-ETAOIN/assets/71267247/3670e51d-f24c-4106-bfb9-132f16d5cd04">

# Choose a password manager

> https://www.lastpass.com/

```
I currently don't use a password manager. But for this assignment, I have chosen LastPass.
It offers great protection against password-related threats. It encrypts sensitive information, provides both free and premium versions, stores data in the cloud with strong security measures.
```

## What threats does it protect against?

```
LastPass protects against threats related to password security, such as:
- Password theft: It securely stores and manages your passwords, making it difficult for attackers to steal them.
- Weak passwords: LastPass can generate strong, unique passwords for each of your accounts
- Phishing attacks: It even helps you avoid entering passwords on fake websites by automatically filling in login credentials only on legitimate sites
```

## What information is encrypted, what's not?

```
LastPass encrypts all the sensitive information it stores, including:
- Usernames and passwords
- Credit card information

What's not encrypted includes:
- Your master password (This is never sent to LastPass, ensuring only you have access.)
- The website URLs you visit (LastPass can autofill login forms on these sites.)
```

## What's the license? How would you describe license's effects or categorize it?

```
LastPass offers both free and premium (paid) versions.
- The free version provides basic password management functionality.
- The premium version, LastPass Premium, offers advanced features like multi-device sync, emergency access, and priority customer support.
- There's also a family plan available for multiple users.
```

## Where is the data stored? If in "the cloud", which country / juristiction / which companies? If on local disk, where?

```
LastPass stores user data in the cloud on their servers. 

LastPass has data centers in a lot of countries, including the United States and Europe. They aim to comply with data protection regulations such as GDPR for European users, which may influence the location of data storage.
```

## How is the data protected?

```
LastPass uses strong encryption algorithms to protect your data:
- Data at rest: Your encrypted data is safely stored on their servers.
- Data in Transit: All encrypted data transfers between your devices and LastPass servers are done using a secure protocol.
- PBKDF2-SHA256 for password hashing (with secure key derivation function).
- Optional two-factor authentication (2FA) for an added security layer.
- LastPass zero-knowledge security model: they don't have access to your master password or your decrypted data, ensuring your privacy.
```

# ETAOIN

HDMH'B TH. KWU'YI AWR WSSTOTMJJK M OWQINYIMLIY! MB KWU BII, BTGPJI BUNBHTHUHTWA OTPDIYB OMA NI NYWLIA RTHD SYIEUIAOK MAMJKBTB. BII KWU MH DHHP://HIYWLMYCTAIA.OWG

```
Alright, let me walk you through how I deciphered this text step by step:

First, I noticed the last part of the text: 'DHHP://HIYWLMYCTAIA.OWG,' which seemed to be a link. Typically, links start with 'http' and end with 'com.'

So, I set up some substitution rules:
D = H
H = T
P = P
O = C
W = O
G = M

To make things clear, I highlighted the letters I changed in bold and took a systematic approach to change one letter at a time.
```

**TH**M**T**'B T**T**. K**O**U'YI A**O**R **O**SST**C**TMJJK M **CO**QINYIMLIY! MB K**O**U BII, BTG**P**JI BUNB**T**T**T**U**T**T**O**A **C**T**PH**IYB **C**NI NY**O**LIA RT**TH **SYIEUIA**C**K MAMJKBTB. BII K**O**U M**T** **HTTP**://**T**IY**O**LMYCTAIA.**COM**

```
Then I look at the first word, which looked like 'THAT.' 

Then, the word right before the link, containing the letter 'T,' seemed to be 'at.' So, I replaced 'M' with 'A.'
```

**THAT**'B T**T**. K**O**U'YI A**O**R **O**SST**C**T**A**JJK**A** **CO**QINYI**A**LIY! **A**B K**O**U BII, BTG**P**JI BUNB**T**T**T**U**T**T**O**A **C**T**PH**IYB **C**NI NY**O**LIA RT**TH SYIEUIA**C**K **A**A**A**JKBTB. BII K**O**U **AT** **HTTP**://**T**IY**O**L**A**YCTAIA.**COM**

```
After the apostrophe in the word, it typically becomes 'That's,' which led me to replace 'B' with 'S.'
```

**THAT'S** T**T**. K**O**U'YI A**O**R **O**SST**C**T**A**JJK **A** **CO**QINYI**A**LIY! **AS** K**O**U **S**II, **S**TG**P**JI **S**UN**ST**T**T**U**T**T**O**A **C**T**PH**IY**S** **C**NI NY**O**LIA RT**TH  SYIEUIA**C**K **A**A**A**JK**S**T**S**. **S**II K**O**U **AT** **HTTP**://**T**IY**O**L**A**YCTAIA.**COM**

```
Next, considering the phrase "That's it," it appears that T should be replaced with I.

The phrase 'That's it' can be read, so I replaced 'T' with 'I.' Now it read, 'It's see you at http:// (link).' So, I substituted 'I' with 'E,' 'K' with 'Y,' and 'U' with 'U.'
```

**THAT'S** **IT**. **YOU**'Y**E** A**O**R **O**SS**ICIA**JJ**Y** **A** **CO**Q**E**NY**EA**LIY! **AS** **YOU** **SEE**, **SI**G**P**J**E** **SU**NS**ITIUTI**OA **CIPHE**Y**S** NY**O**L**E**A R**ITH  SYIE**UE**A**CY** **A**A**A**J**YSIS**. **SEE YOU AT** **HTTP**://**TE**Y**O**L**A**YC**I**A**E**A.**COM**

```
In the context of our course, I deduced that:

'SIGPJE' corresponds to 'SIMPLE,' implying 'G' should be 'M,' and 'J' should be 'L.'
'AAAYJSIS' can be read as 'ANALYSIS,' indicating 'A' should be 'N.'

Therefore, I updated the substitutions:

A = N
G = M
J = L
```

**THAT'S** **IT**. **YOU**'Y**E** **NO**R **O**SS**ICIALLY** **A** **CO**Q**E**NY**EA**LIY! **AS** **YOU** **SEE**, **SIMPLE** **SU**NS**ITIUTI**O**N** **CIPHE**Y**S** NY**O**L**EN** R**ITH SYIE**UENCY** **ANALYSIS**. **SEE YOU AT** **HTTP**://**TE**Y**O**L**A**YC**INEN.COM**

```
I then realized that the link is 'TEROKARVINEN.COM,' so I made the final substitutions:

Y = R
L = K
C = V
```

**THAT'S** **IT**. **YOU'RE** **NO**R **O**SS**ICIALLY** **A** **CO**Q**E**N**REAKER**! **AS** **YOU** **SEE**, **SIMPLE** **S**U**NS**ITIUTI**OA** **CIPHERS** **BROKEN** R**IIH** S**R**IE**UENCY** **ANALYSIS**. **SEE YOU AT** **HTTP**://**TEROKARVINEN.COM**

```
Then also with the context of our last course, i deduced that:

SUNSITIUTIOA = SUBSTITUTION
SRIEUENCY = FREQUENCY

S = F
Q = D
N = B
E = Q
R = W

In the end, I successfully deciphered the message, which reads: THAT'S IT. YOU'RE NOW OFFICIALLY A CODEBREAKER! AS YOU SEE, SIMPLE SUBSTITUTION CIPHERS BROKEN WITH FREQUENCY ANALYSIS. SEE YOU AT HTTP://TEROKARVINEN.COM.
```

```
Below is a summary of the letter substitutions:

A = N
B = S
C = V
D = H
E = Q
G = M
H = T
I = E
J = L
K = Y
L = K
M = A
N = B
O = C
P = P
Q = D
R = W
S = F
T = I
U = U
W = O
Y = R
```

# Demonstrate the use of a password manager

```
Here is a step-by-step instructions on how to use a password manager like LastPass to store and manage your passwords. 
```

## Step 1:  

Go to https://www.lastpass.com/products/personal

<img width="306" alt="image" src="https://github.com/piafernandez/h4-ETAOIN/assets/71267247/39be171f-3308-44f4-b4fb-5e0cf09d57bc">

## Step 2: Set Up a Master Password

Click on Start Families Trial and create an account.

<img width="264" alt="image" src="https://github.com/piafernandez/h4-ETAOIN/assets/71267247/fdd74dac-7040-42dd-bb15-7cc4be29dcb0">

```
During the setup process, you'll be asked to create a strong and memorable master password. This is the only password you'll need to remember.

Ensure that your master password is unique and not used elsewhere.
```

## Step 3 Install or add the extension to your browser

<img width="412" alt="image" src="https://github.com/piafernandez/h4-ETAOIN/assets/71267247/f8ac0447-7a1f-479b-b379-0cf66d23b22b">

## Step 4: Save Your First Login Credentials

```
As you browse the web and log in to different websites, the password manager will detect login forms and offer to save your login credentials.

When prompted, choose to save the login details for the website.
```



<img width="379" alt="image" src="https://github.com/piafernandez/h4-ETAOIN/assets/71267247/c4a68d56-d7fa-408c-bf6c-cd0c33136085">
<img width="248" alt="image" src="https://github.com/piafernandez/h4-ETAOIN/assets/71267247/cce501b5-f6ee-4253-85d0-0307399cd684">

```
Here you can see the the site and log in details have been added to my LastPass account.
```
<img width="446" alt="image" src="https://github.com/piafernandez/h4-ETAOIN/assets/71267247/f3904c43-c85a-485d-a564-bd8d7f040721">




## **Step 5: Auto-Fill Login Credentials**

```
When you revisit a website where you've saved login credentials, the password manager will automatically fill in the username and password fields for you.
```

```
You may need to authenticate using your master password to unlock access to your stored passwords.
```

<img width="281" alt="image" src="https://github.com/piafernandez/h4-ETAOIN/assets/71267247/afc5e8a1-4f59-426f-ad52-4a38e6981dd5">



## **Step 6: Generate Strong Passwords**

```
When creating new accounts or updating passwords, use the password manager's password generator to create strong, unique passwords.

The password manager will save these generated passwords for you.
```

<img width="287" alt="image" src="https://github.com/piafernandez/h4-ETAOIN/assets/71267247/b6c82e1c-bf91-406a-9ed2-31c674e23cfb">

# Encrypt and decrypt a message + Bonus: send and receive encrypted message over email

```
I chose GPG for this demonstration because it's a widely used and trusted encryption tool that provides both symmetric and asymmetric encryption capabilities, making it suitable for secure message exchange. Additionally, it's available on multiple platforms and can be used via the command line, which provides a transparent view of the encryption process.
```

## 1. Open your virtual machine and the terminal

## 2. Install GPG

![image-20230916161731393](C:\Users\ferna\OneDrive - HESSO\Documents\02_School\00_HAAGA-HELIA\Semester VII\01_Information Security - Tero Karvinen\01_Assignments\h4\h4\image-20230916161731393.png)

![image-20230916161811390](C:\Users\ferna\OneDrive - HESSO\Documents\02_School\00_HAAGA-HELIA\Semester VII\01_Information Security - Tero Karvinen\01_Assignments\h4\h4\image-20230916161811390.png)

```
Note that I already have downloaded this in class.
```

## 2. Generate a key pair

> This step creates a pair of keys for encryption and decryption. The private key is kept secret and is used for decryption, while the public key is shared with others for encrypting messages to you.

![image-20230916161949283](C:\Users\ferna\OneDrive - HESSO\Documents\02_School\00_HAAGA-HELIA\Semester VII\01_Information Security - Tero Karvinen\01_Assignments\h4\h4\image-20230916161949283.png)

```
Set a passphrase for your private key. This passphrase is used to protect your private key and should be kept secret. For this example, I didn't  put a passphrase.
```

## 3. Export public key 

![image-20230916162040292](C:\Users\ferna\OneDrive - HESSO\Documents\02_School\00_HAAGA-HELIA\Semester VII\01_Information Security - Tero Karvinen\01_Assignments\h4\h4\image-20230916162040292.png)

![image-20230916162117243](C:\Users\ferna\OneDrive - HESSO\Documents\02_School\00_HAAGA-HELIA\Semester VII\01_Information Security - Tero Karvinen\01_Assignments\h4\h4\image-20230916162117243.png)

```
Once your key pair is generated, you can list your keys with:    
gpg --list-keys
```

![image-20230916162245185](C:\Users\ferna\OneDrive - HESSO\Documents\02_School\00_HAAGA-HELIA\Semester VII\01_Information Security - Tero Karvinen\01_Assignments\h4\h4\image-20230916162245185.png)

## 4. Import public key of the recipients

```
You need to import your recipients public key so you can encrypt your message with it.
```

![image-20230916162418187](C:\Users\ferna\OneDrive - HESSO\Documents\02_School\00_HAAGA-HELIA\Semester VII\01_Information Security - Tero Karvinen\01_Assignments\h4\h4\image-20230916162418187.png)

```
You need to press CTRL + D after this command !
```

## 5. Verify the key

![image-20230916162454869](C:\Users\ferna\OneDrive - HESSO\Documents\02_School\00_HAAGA-HELIA\Semester VII\01_Information Security - Tero Karvinen\01_Assignments\h4\h4\image-20230916162454869.png)

```
Now her public key is in my list: 
```

![image-20230916162552436](C:\Users\ferna\OneDrive - HESSO\Documents\02_School\00_HAAGA-HELIA\Semester VII\01_Information Security - Tero Karvinen\01_Assignments\h4\h4\image-20230916162552436.png)

## 5. Encrypt a Message

> Encrypting the message with the recipient's public key ensures that only the recipient, who possesses the corresponding private key, can decrypt and read it.

![image-20230916162805393](C:\Users\ferna\OneDrive - HESSO\Documents\02_School\00_HAAGA-HELIA\Semester VII\01_Information Security - Tero Karvinen\01_Assignments\h4\h4\image-20230916162805393.png)

```
Now type your message then press CTRL + D
```

![image-20230916162835224](C:\Users\ferna\OneDrive - HESSO\Documents\02_School\00_HAAGA-HELIA\Semester VII\01_Information Security - Tero Karvinen\01_Assignments\h4\h4\image-20230916162835224.png)

```
You can now copy this message, note that you need to copy everything.
```

##  6. Decrypt a message

> Decrypting the message with your private key allows you to recover the original plaintext message.

```
I have received a message via email. But the message is encrypted. The sender used my public key to encrypt the message. 
```

![image-20230916163451887](C:\Users\ferna\OneDrive - HESSO\Documents\02_School\00_HAAGA-HELIA\Semester VII\01_Information Security - Tero Karvinen\01_Assignments\h4\h4\image-20230916163451887.png)

```
Now I use the command below that will use my private key to decrypt the message.
```

![image-20230916163517102](C:\Users\ferna\OneDrive - HESSO\Documents\02_School\00_HAAGA-HELIA\Semester VII\01_Information Security - Tero Karvinen\01_Assignments\h4\h4\image-20230916163517102.png)

# Sources and links

- *CHAPTER 1: Foundations - Applied Cryptography: Protocols, Algorithms and Source Code in C, 20th Anniversary Edition [Book]*. https://www.oreilly.com/library/view/applied-cryptography-protocols/9781119096726/08_chap01.html. Accessed 16 Sept. 2023.
- ‘Fréquence d’apparition des lettres’. *Wikipédia*, 24 June 2023. *Wikipedia*, https://fr.wikipedia.org/w/index.php?title=Fr%C3%A9quence_d%27apparition_des_lettres&oldid=205432810.
- *Last Pass* https://www.lastpass.com Accessed 16 Sept. 2023.
- *ChatGPT - OpenAI* [ChatGPT (openai.com)](https://chat.openai.com/?model=text-davinci-002-render-sha) Accessed 16 Sept. 2023.

