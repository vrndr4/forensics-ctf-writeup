## Challenge Info

**Title:** Secret of the Polyglot 
**Category:** Forensics  
**Difficulty:** Easy  
**Description:* The Network Operations Center (NOC) of your local institution picked up a suspicious file, they're getting conflicting information on what type of file it is. They've brought you in as an external expert to examine the file. Can you extract all the information from this strange file?

## Solution

I'm actually familiar with the tools and tricks used in this challenge.  
This challenge provided a PDF file that only consists of 1n_pn9_&_pdf_7f9bccd1} which is probably a part of the real flag as it matches with the usual format and pattern.  
So then I tried looking into the metadata and found nothing. I proceed to use binwalk to see if there are any other files inside of the pdf (if that makes sense).  
<img width="826" height="148" alt="image" src="https://github.com/user-attachments/assets/6072f8ca-8732-4e97-aa7f-7ce8352ef0e5" />  
Turns out there's a png file inside so I knew I had to open it as I believe it contains the first part of the flag.  
Because the PDF starts at byte 914, I saved the first 914 as png using:  
dd if=flag2of2-final.pdf of=part1.png bs=1 count=914  

<img width="50" height="50" alt="part1" src="https://github.com/user-attachments/assets/efc9a4df-a49e-48ed-a445-b303ed6dd3de" />

And there's the results. Combining the png and the pdf makes the flag.

## Flag

picoCTF{*************_&_pdf_7f9bccd1}

## Comment

Pretty cool challenge. I like challenges where the files are hidden inside of files. Though I had to search how to extract the png file, but I still get the flow of the chall.
