## Challenge Info

**Title:** RED  
**Category:** Forensics  
**Difficulty:** Easy  
**Description:*
RED, RED, RED, RED

## Solution

This challenge had an image attached to it. Basically it's called red.png with the color red. Literally.  
<img width="128" height="128" alt="red" src="https://github.com/user-attachments/assets/e985cdb9-52a7-4623-93be-603c21a2df2f" />  
First thing I did as usual is check the exiftool. Surprisingly, there is a poem inside it.
<img width="1002" height="486" alt="image" src="https://github.com/user-attachments/assets/4739f996-8d11-4b32-99c7-77babf747fee" />
This poem looks weird and my first instinct was to look at the capital letters and it showed "CHECKLSB".  
I checked the LSB where the color is inverted etc but found nothing. So I searched the internet on what to do and was told to do zsteg.  
<img width="1097" height="419" alt="image" src="https://github.com/user-attachments/assets/d9980e7c-cd5a-405f-9cb7-dc7d07584627" />
The text in red looks weird so I decoded it and found the flag:  
<img width="980" height="506" alt="image" src="https://github.com/user-attachments/assets/2a4153e0-78b2-47d5-9534-b10b7bd8bfc1" />

## Flag

picoCTF{r3d_1s_th3_ult1m4t3_cur3_f0r_54dn355_}

## Comment

Not the toughest so far. Pretty cool to memorize some stuff in Linux.
