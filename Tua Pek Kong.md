This challenge is categorize in steganography.

After receiving the file given, there is no available extension .__.

Therefore, the file was scanned using linux "file" command.


![Screenshot 2024-04-28 210132](https://github.com/Cryogas/GDSC_CTF_APR_2024/assets/136941894/2845bab4-a592-4e3e-90b9-f12f8538ce4a) (r u kidding me..)

Hexdump is used next, and this is shown

![Screenshot 2024-04-28 210502](https://github.com/Cryogas/GDSC_CTF_APR_2024/assets/136941894/a30a2ff0-4b4b-4ab4-900d-67a1e587224a)

Its a JFIF (JPG) file, but the header is not the usual signature...
![Screenshot 2024-04-28 210708](https://github.com/Cryogas/GDSC_CTF_APR_2024/assets/136941894/0cb8b4cb-3610-4c0f-9820-cab0b2faed5e)

SO I CHANGED IT USING TEXT EDITOR, AND I SAVED IT.


![a](https://github.com/Cryogas/GDSC_CTF_APR_2024/assets/136941894/e2c2be6d-1f55-46d9-be47-7402e5751cd0)

PART 1 of the flag, cool 😎

I remember there is a passphrase given ... 🤔
Must be useful


![Screenshot 2024-04-28 211037](https://github.com/Cryogas/GDSC_CTF_APR_2024/assets/136941894/983b0768-0c67-44ab-9371-cf827c345b64)


Search for a stega solver online.. decided to use this website : https://futureboy.us/stegano/decinput.html 

Upload the .jpg file and insert the passphrase...

![Screenshot 2024-04-28 211122](https://github.com/Cryogas/GDSC_CTF_APR_2024/assets/136941894/d7a950f2-a314-455d-8afd-cf7de35750da)


......

Voila ! 🥳🥳🥳

![Screenshot 2024-04-28 211236](https://github.com/Cryogas/GDSC_CTF_APR_2024/assets/136941894/0ef090cc-8b00-41c2-aec7-b7cbf0a56ccb)


FLAG: GDSC{r3sPeCt_y0uR_e1d3Rs}


Conclusion: This challenge is difficult as knowledge about file header signatures and solving steganography tools are required for this 
challenge. 

