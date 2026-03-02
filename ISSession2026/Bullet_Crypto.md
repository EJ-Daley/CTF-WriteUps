# CTF Write Up

## Challenge Info
**Name:** Generic Bullet Hell Crypto Game  
**Category:** Wizard Games  
**Event:** ISSessions 2026  
**Completed:** Yes  

## Challenge Description
>can you beat the game?

---

## Investigation
There is a fun way and an efficent way to solve this challenge.

The fun way involves beating 10 waves of a bullet hell game, then decrypting a cipher, the decryption methods for each level are;
1. From Base64
2. From Hex
3. Rot 13
4. From Binary
5. From Base64, then reversed
6. From Morse *Formatting will need to be changed since curly brackets are replaced with regular brackets in morse code.
7. Vigenere Decode with key "CTF"
8. From Base32
9. From Hex, then reversed
10. Either you dont need to decipher a code on this round or I forgot to make a note of it.

The alternative solution is to ctrl+f search FantasyCTF in the source code since the flag is in plaintext
put image

Additionally you can find the case then encodes the flags which tells you how to decrypt all if you didnt feel like figuring it out.
put image

---

## Outcome
**Flag:** FantasyCTF{C0ngraTulations_On-Winning}
