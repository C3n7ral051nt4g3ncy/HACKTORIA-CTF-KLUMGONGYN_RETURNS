# HACKTORIA CTF
CTF Writeup : **KLUMGONGYN RETURNS**

Classed on the Hacktoria website as level: `Insane`

<br>

<img width="633" src="https://user-images.githubusercontent.com/104733166/190494089-aaa3da3c-e570-4379-8a63-e2cd04978240.png">



<br>

<img width="433" src="https://user-images.githubusercontent.com/104733166/190491622-a87fce32-f59f-4386-b08c-c2b8feb7f79f.jpg">

# Mission | Task 

Greetings Special Agent K. We have a very special assignment for you today. You might remember our old friend Klumgongyn. He’s recently turned up again and will be cooperating with us going forward. In what capacity that collaboration is, I cannot say right now.

All I can tell you, that below you’ll find a text written in ancient Klumgon. It’s up to you to translate the text, which will help you uncover the password for your Link File as well.

Everything else will become clear upon translating the text.

As always. Special Agent K, the contract is yours, if you choose to accept.

<br>

# Ancient Alien Language Decryption 

<img width="433" src="https://user-images.githubusercontent.com/104733166/190492182-a2baa584-e1dc-4641-b8d4-617633229503.jpg">

<br>

# Capturing the Flag

I initially thought there was steganography in this image as Zsteg detected Steg inside and a secret PGP Key which I have not seen before on images that didn't contain STEGO.

But I worked only from the file, and decrypted the text in full.
This is what the image looked like after decryption (see below), I wrote above each sentence in bright green. (**I have put this image in small as the CTF is still running**).

<img width="67" src="https://user-images.githubusercontent.com/104733166/190493098-62705efc-b404-4415-9092-dfd922420e7a.png">
 
Once the text was fully decrypted, a password was found in order to open the encrypted `.zip file`, there is specific characters that were not that easy to find, but after doing a few tweaks, the  `.Zip file` opened.
 
Once the zip decrypted, there is an `exec file` , by clicking on it the terminal is opened and we get a `bit.ly` link, with the bit.ly link we can then get the  `Contract Card`.

<img width="233" src="https://user-images.githubusercontent.com/104733166/190493761-f4a4a96c-bed5-4cd1-82a3-a1ffb64054cc.png">

<br>

# Contract Card

<img width="433" src="https://user-images.githubusercontent.com/104733166/190493907-a1c753ad-01c2-471b-83d9-9f4f5ee38fe5.png">


