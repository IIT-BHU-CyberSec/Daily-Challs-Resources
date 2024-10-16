# Ciphers - Introduction

A cipher is basically **an algorithm for encryption and decryption**. An **algorithm** is nothing but a series of steps to perform something, in our case encryption and decryption. Now the question is whats encryption/decryption.

**Encryption** is the process of transforming information in a way that only authorized parties can decode. The process of decoding is what's called **Decryption**.

Lets see this with an example, 
Assume I define a new cipher, the wordplay cipher. This is a ciphertext (encrypted message) generated using this cipher

```
only love leads to hope
```
Did you find something?
Now what might seem like a rather controversial statement is actually a message. Wait let me make things easier.
```
Only Love Leads To Hope
```
See something now?
Focus on the first letter and separate them out.
```
OLLEH
```
Reverse it and voila we get a beautiful `HELLO`!

Now this might seem strange. Only I knew the cipher, there was not much you could do right. But that's a power, now I can share the cipher technique with only the people I want to see the hidden message. The rest won't know!

Now, from a security point of view, seeing such messages and guessing the cipher is a powerful tool to have. Imagine spying on someone's secrets :)

However, this is not always random. Most of the times, people use common ciphers or make their own ciphers by combining various ciphers. Today's challenge has a ciphertext which is nothing but the flag (the answer to the challenge that you have to submit) encrypted. Some other hints in the challenge might help you find the cipher!

