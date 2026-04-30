## Challenge Info

**Title:** What Lies Within  
**Category:** Forensics  
**Difficulty:** Medium  
**Description:** There's something in the building. Can you retrieve the flag?

## Solution

The challenge was provided with a png. The clue said that there's something in the building and I immediately thought of putting it into lsb, but I did strings first although nothing was there. I also tried binwalk and exiftool and nothing was there.  
So I went to Aperisolve to try and find the flag in different versions of the image, but found nothing. Until:  
<img width="1213" height="364" alt="image" src="https://github.com/user-attachments/assets/845e6354-6506-4ef0-8eab-c9b333922872" />  
Turns out it was in the zsteg. Flag found.

## Flag

`picoCTF{h1d1ng_1n_***_****}`

## Comment

Should've trusted my first gut.
