## Challenge Info

**Title:** information  
**Category:** Forensics  
**Difficulty:** Easy  
**Description:** Files can always be changed in a secret way. Can you find the flag?

## Solution

The challenge gave a jpg file called cat.jpg so at first glance I thought I had to cat the image but I didn't do it.  
So I do what I usually do first, which is exiftool the image and found a weird string.
<img width="785" height="96" alt="image" src="https://github.com/user-attachments/assets/b5125079-eedd-4732-8d17-0e3c27522c13" />  
My first instinct was to decode this and yeah there's the flag.  
<img width="980" height="512" alt="image" src="https://github.com/user-attachments/assets/71194894-c22c-41b7-8f60-bd004cd3c2bd" />

## Flag

picoCTF{the_m3tadata_1s_modified}

## Comment

Pretty easy no cap.
