# QESencryption
Qamarz Encryption Scheme without key.  (Currently in JAVA only)

This encryption scheme has only two public methods encrypt and decrypt which will allow you to encrypt and decrypt any string without asking you for a key. You can easily encrypt or decrypt any string with full security (i.e 128bit+ encryption). 

How to use QESencryption:

1. Add QESencryption class to your java project.
2. Make an instance of it.
3. Call encrypt method which takes one String parameter to be encrypted and call decrypt method which takes encrypted string parameter to be decrypted.

example:

QESencryption qes = new QESencryption();
String plainText = "Hello World!";
String encryptedText = qes.encrypt(plainText);
System.out.println(qes.decrypt(encryptedText);
