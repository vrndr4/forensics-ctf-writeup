## Challenge Info

**Title:** Corrupted file  
**Category:** Forensics  
**Difficulty:** Easy  
**Description:** This file seems broken... or is it? Maybe a couple of bytes could make all the difference. Can you figure out how to bring it back to life?

## Solution

This wasn't easy to say the least. I had no idea what to do only by the file given, so I looked at the 3 hints and searched it up. Turns out, I should change the bytes.  
A real jpeg starts with FF D8 FF E0, so I basically changed those digits and made it a jpg file.  
After that, a new file appears in my File Explorer containing the flag.  
<img width="338" height="121" alt="image" src="https://github.com/user-attachments/assets/5540d62b-9289-4141-9e4f-a8bac2af7765" />

## Flag

`picoCTF{r3st0r1ng_th3_by73s_********}`

## Comment

(comment)
