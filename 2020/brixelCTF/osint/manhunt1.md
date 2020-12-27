# Manhunt 1

Category: OSINT

Points: 5

Attached File: [icecream.jpg](files/icecream.jpg) 

Description:

> My dad is pissed off! He was told by my mother NOT to buy ice cream but he did anyway when she wasn't looking.

> Someone posted this picture on the internet and my mother saw it, man, he is in so much trouble!

> I want to know WHO posted this picture, let's hunt this guy down!

## Solution

I'll download the picture file from the problem then used exiftool to see the metadata. 

![icecream](files/icecream.jpg)

The metadata of the picture show the owner name.

![metadata](files/exif_manhunt1.PNG)

The flag is `brixelCTF{Johnny_Dorfmeister}`

