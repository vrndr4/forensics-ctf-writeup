## Challenge Info

**Title:** Matroyshka Doll  
**Category:** Forensics  
**Difficulty:** Medium  
**Description:**  Matryoshka dolls are a set of wooden dolls of decreasing size placed one inside another. What's the final one?

## Solution

I downloaded the image given and tried to exiftool it but nothing really appears. My next instinct was to look at the properies but nothing really showed up as well.  
I then proceed to do binwalk and found something.  
<img width="1101" height="139" alt="image" src="https://github.com/user-attachments/assets/c55df71a-7915-49e1-ada0-caab9ce4c0f0" />  
Oh there's something there. I went on and did  binwalk -Me dolls.jpg and it keeps showing the same thing. I didn't realize at first what a Matroyshka Doll is and here is where I figured it out. I had to do this procedure multiple times to hopefully get to the smallest doll and receive the flag.  
So I did it repeatedly about 4 times and got flag.txt (finally).  
<img width="1099" height="153" alt="image" src="https://github.com/user-attachments/assets/d7540e71-7e3b-4032-8444-5cd3374cb5b3" />

## Flag

`picoCTF{LL9lb1dR4QbGe4l4i***************}`

## Comment

Pretty easy honestly, just kinda tiring.
