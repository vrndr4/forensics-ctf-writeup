## Challenge Info

**Title:** extensions  
**Category:** Forensics  
**Difficulty:** Medium  
**Description:** This is a really weird text file. Can you find the flag?
Get the flag from TXT.

## Solution

First thing I did was binwalk the txt file and found something, but when I binwalk -e'd the thing, it won't appear. So I looked up how to do this and I found out I had to change the file format from flag.txt to flag.png in order to access the png, because it was originally a png.   
<img width="823" height="355" alt="image" src="https://github.com/user-attachments/assets/7c2de831-d15e-4d7a-825b-2b573cc1a4f6" />
And just like that, I got the flag.

## Flag

`picoCTF{now_you_know_*****_**********}`

## Comment

Had to look it up. But it was okay.
