# Mechanics of Multiplicity Cipher

* **How does the Cipher work?**
  * It works by encrypting and decrypting symbols and converting the values into numbers. 
  * When mulitiplication is used to convert to cipher test. It is called a wrap-around situation.

**Consider the numbers and asscociated letters to be used as shown**

![Number Table](https://www.tutorialspoint.com/cryptography_with_python/images/associated_numbers.jpg)

Using the numbers from the table, we can use this basic python formula to generate a multiplicative cipher 

**(Alphabet Number * key)mod(total number of alphabets)**

The number fetched through output is mapped in the table mentioned belowand the corresponding letter is taken as the encrypted letter.

![encryption graph](https://www.tutorialspoint.com/cryptography_with_python/images/encrypted_letter.jpg)

Heres a basic modulation function of a multiplcative cipher in python

**def unshift(key, ch):**

   **offset = ord(ch) - ASC_A**
   
   **return chr(((key[0] * (offset + key[1])) % width) + ASC_A)**
[A link to encoding and decoding](https://www.ti89.com/cryptotut/multi4.htm)


