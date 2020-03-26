# 🔑 Encoding By RSA Method

<img src="https://image.flaticon.com/icons/png/512/2092/2092480.png" width="250">

# 📝 ***Introduction:***

<br>***• Differentiate symmetric and asymmetric encryption***

***• understand RSA encryption***

***• Mathematical interpretation***

# 🔎 Symmetric or Asymmetric Encryption ? 

***To start this introduction to RSA, we need to understand the difference between these two types of encryption.***

# ***1] What is Symmetric Encryption?***

***Symmetric cryptography, also known as secret key, is the oldest form of encryption. It allows you to both encrypt and decrypt messages using the same keyword. One of the fundamental concepts of symmetric cryptography is the key. A key is a piece of data which (processed by an algorithm) makes it possible to encrypt and decrypt a message. Not all encryption methods use a key. The ROT13, for example, has no key. Anyone who discovers that a message has been coded with this algorithm can decrypt it without further information. Once the algorithm is discovered, all messages encrypted by it become readable. Here is an explanatory diagram:***

<img src="https://www.ibm.com/support/knowledgecenter/SSB23S_1.1.0.13/gtps7/ssldig01.gif" width="500">

# ***2] What is asymmetric encryption?***

***Unlike symmetric cryptography, here with asymmetric, we have 2 keys.***
***First we have the public key. Anyone can own it, there is no risk, you can pass it on to anyone. It is used to encrypt the message. Then there is the private key that only the receiver has, in this case you. It will be used to decrypt the message encrypted with the public key. Here is an explanatory diagram:***

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/40/Chiffrement_asym%C3%A9trique.jpg/661px-Chiffrement_asym%C3%A9trique.jpg" width="650">

# 🔐 *What is RSA Encryption?*

<img src="https://image.flaticon.com/icons/png/512/2092/2092570.png" width="200">

***RSA encryption (named by the initials of its three inventors [Ronald Rivest; Adi Shamir; Leonard Adleman]) is an asymmetric cryptography algorithm, because it has two keys, a public key and a private key.***
***RSA encryption uses a key pair (whole numbers) consisting of a public key to encrypt and a private key to decrypt confidential data. The two keys are created by a person, often by convention Alice, who wishes confidential data to be sent to her. Alice makes the public key accessible. This key is used by his correspondents (Bob, etc.) to encrypt the data sent to him. The private key is reserved for Alice, and allows her to decrypt this data. The private key can also be used by Alice to sign data that it sends, the public key allowing any of its correspondents to verify the signature.***

***An essential condition is that it is "calculatively impossible" to decrypt using the public key alone, in particular to reconstitute the private key from the public key, that is to say that the means of calculation available and known methods at the time of the exchange (and the time that the secret must be kept) do not allow it.***
***Alice is responsible for creating the keys. It does not intervene with each encryption because the keys can be reused. The first difficulty, which encryption does not solve, is that Bob is quite certain that the public key he holds is that of Alice. The renewal of the keys occurs only if the private key is compromised, or as a precaution after a certain time (which can be counted in years).***

# 📚 *Mathematical Interpretation*
***To understand this interpretation see:***


<a href="https://en.wikipedia.org/wiki/Congruence">**Congruence**</a><br>
<a href="https://en.wikipedia.org/wiki/Modulo_operation">**Modulo Operation**</a><br>
<a href="https://en.wikipedia.org/wiki/Euler%27s_totient_function">**Euler's totient function**</a><br>
<a href="https://en.wikipedia.org/wiki/Prime_number">**Prime Numbers**</a>

<img src="https://i.ytimg.com/vi/-jSX9fNJiN8/maxresdefault.jpg" width="600">
<a href="https://instagram.com/pyr3q">***Made By PyR3Q***</a>
