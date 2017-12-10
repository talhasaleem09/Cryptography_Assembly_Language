# Assembly Language Assignment

This is an assembly language program that was assigned to me as an assignment for my college course named "Assembly Language Programming". I've implemented one of the oldest cipher named as Caesar Cipher.

Ceasar Cipher is a type of substitution cipher in which each letter in the plaintext is replaced by a letter some fixed number of positions down the alphabet. For example, with a left shift of 3, D would be replaced by A, E would become B, and so on. The method is named after Julius Caesar, who used it in his private correspondence.

For Example:

## Encryption:

Formula: En = (x+n) mod(26)

Key = 3 left shift

Plaintext:  THE QUICK BROWN FOX JUMPS OVER THE LAZY DOG
Ciphertext: QEB NRFZH YOLTK CLU GRJMP LSBO QEB IXWV ALD

## Decryption

Formula: Dec = (x-n) mod(26)

Key = 3 Right shift

Encrypted text: QEB NRFZH YOLTK CLU GRJMP LSBO QEB IXWV ALD
Decryption:  THE QUICK BROWN FOX JUMPS OVER THE LAZY DOG


