## Challenge Info

**Title:** Flag in Flame  
**Category:** Forensics  
**Difficulty:** Easy  
**Description:*
The SOC team discovered a suspiciously large log file after a recent breach. When they opened it, they found an enormous block of encoded text instead of typical logs. Could there be something hidden within? Your mission is to inspect the resulting file and reveal the real purpose of it. The team is relying on your skills to uncover any concealed information within this unusual log.
Download the encoded data here: Logs Data. Be prepared—the file is large, and examining it thoroughly is crucial .

## Solution

I opened the log data and had no idea what that is so I had to search it up a bit. I was told that the file begins with a base64 data. I then converted the logs to the original data which is an image using base64 -d.  
I got the png image.  
<img width="896" height="1152" alt="log" src="https://github.com/user-attachments/assets/7be279e7-7abc-4db9-b43f-f4c43577880f" />  
Surely those numbers look weird but I had no clue what those numbers are. I looked it up again and it is actually hexadecimal (base16) encoding.  
So I decoded it using echo (numbers and letters) | xxd -r -p and found the flag.  
<img width="1091" height="66" alt="image" src="https://github.com/user-attachments/assets/23392283-0c5d-491d-a1db-8f68e8d92c58" />

## Flag

picoCTF{forensics_analysis_is_amazing_24d16895}

## Comment

Pretty cool challenge. I learned how to decode base16, hex, do lsb, do base64, turn log into img, and so on.
