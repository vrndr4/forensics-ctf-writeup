## Challenge Info

**Title:** Verify  
**Category:** Forensics  
**Difficulty:** Easy  
**Description:** People keep trying to trick my players with imitation flags. I want to make sure they get the real thing! I'm going to provide the SHA-256 hash and a decrypt script to help you know that my flags are legitimate.
Additional details will be available after launching your challenge instance.

## Solution

This challenge provides a folder containing many files, a SHA-256 checksum of the correct file, and a script called decrypt.sh to decrypt the correct file.  
First step is to find the correct file containing the SHA-256 checksum. To do that:  
sha256sum files/* | grep 5848768e56185707f76c1d74f34f4e03fb0573ecc1ca7b11238007226654bcda  
<img width="1091" height="60" alt="image" src="https://github.com/user-attachments/assets/e49e97bf-f4d6-4192-9eae-ab874fad943b" />
Turns out it belongs to 8eee7195  
The next step is to decrypt the file:  
<img width="508" height="44" alt="image" src="https://github.com/user-attachments/assets/426dc8ed-fa69-47fa-814c-f75ecc0cb630" />  
And there's the flag

## Flag

picoCTF{trust_but_verify_********}

## Comment

This was actually short, easy, and understandable but I had to get help from AI because I don't really know the basics yet. It was a cool challenge tho.
