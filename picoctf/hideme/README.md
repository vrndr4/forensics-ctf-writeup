## Challenge Info

**Title:** hideme  
**Category:** Forensics  
**Difficulty:** Medium  
**Description:** Every file gets a flag. The SOC analyst saw one image been sent back and forth between two people. They decided to investigate and found out that there was more than what meets the eye here.

## Solution

This one's actually pretty simple. The challenge gave an image which first I did exiftool and checked the properties but nothing really came up.

Then I tried binwalk and there were some things so I just extracted it and see what was there. 

<img width="856" height="443" alt="image" src="https://github.com/user-attachments/assets/efaba162-2ecd-42a2-a293-cf3561550751" />

<img width="473" height="241" alt="image" src="https://github.com/user-attachments/assets/b59e5f95-72fa-477f-b4a6-049ad9d2f8d2" />

Turns out, I got the flag in the secret folder, containing an image of the flag.

## Flag

picoCTF(Hiddinng_An_imag3_within_@n_image_********}

## Comment

Kinda easy. Though needed some insights because I kinda blanked in the beginning.
