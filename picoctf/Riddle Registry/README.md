## Challenge Info

**Title:** Riddle Registry  
**Category:** Forensics  
**Difficulty:** Easy  
**Description:** Hi, intrepid investigator! 📄🔍 You've stumbled upon a peculiar PDF filled with what seems like nothing more than garbled nonsense. But beware! Not everything is as it appears. Amidst the chaos lies an elusive flag waiting to be uncovered. Find the PDF file here Hidden Confidential Document and uncover the flag within the metadata.

## Solution

First, the challenge was provided with a PDF file that looks like this:  
<img width="550" height="705" alt="image" src="https://github.com/user-attachments/assets/fcbddfbc-4cb4-4cc1-8688-f19a70c36d1a" />  
I read the letter but didn't really think much of it because the challenge description said "uncover the flag within the metadata".  
First thing I did was look at the file's properties but nothing was found.  
My next intuition was to do an exiftool using Ubuntu and I found something.  
<img width="907" height="336" alt="image" src="https://github.com/user-attachments/assets/8cf26f39-36d6-4922-b028-8034bc02582b" />  
The author name does look pretty suspicious so I knew it had to be some sort of code, but didn't know what it was so I just went to Google and search "decode code" and cliked on the first thing that popped up.  
Pasted the author name, decoded it and found the flag.  
<img width="1375" height="752" alt="image" src="https://github.com/user-attachments/assets/eb322d09-1eaf-4888-8c99-f987aabbb7ff" />  

## Flag

Flag: picoCTF{puzzl3d_m3tadata_f0und!_********}

✔ Metadata inspected and anomalous entries identified  
✔ Embedded information extracted successfully  
✔ Output matched expected structure and validated

## Comment

Wasn't that tough actually. I did this challenge before a long time ago but still managed to do it quick.

