## Challenge Info

**Title:** Hidden in plainsight  
**Category:** Forensics  
**Difficulty:** Easy  
**Description:** You’re given a seemingly ordinary JPG image. Something is tucked away out of sight inside the file. Your task is to discover the hidden payload and extract the flag.  

## Solution

A jpg file was given and it is said that the answer might be "inside the file". So I did exiftool on this image again and found something suspicious.  
<img width="751" height="528" alt="image" src="https://github.com/user-attachments/assets/3b8b6675-6072-41db-b513-9ea3576379a2" />  
I went to decoder again and found this  
<img width="979" height="519" alt="image" src="https://github.com/user-attachments/assets/6d3b584b-6012-4cbe-9a9e-fcdd5a2f37d8" />  
It still looked suspicious so I decoded the cEF6endvcmQ=  
<img width="981" height="503" alt="image" src="https://github.com/user-attachments/assets/3d22028c-5b62-4e25-8a67-133f01c4a65d" />  
I've rarely used steghide before so I looked it up and went on to steghide the jpg file using that as the password and found the flag.  
<img width="866" height="184" alt="image" src="https://github.com/user-attachments/assets/69f1ad36-adbf-445c-a25c-506963e5ae34" />


## Flag

`picoCTF{h1dd3n_1n_1m4g3_********}`

✔ Hidden content detected within image file  
✔ Extracted using steganography techniques  
✔ Result decoded and validated successfully

## Comment

It was alright. I'm still new to Forensics so had to look up how to use steghide. Overall still easy though.
