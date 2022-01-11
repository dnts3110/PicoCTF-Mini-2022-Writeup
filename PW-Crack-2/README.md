# Question
![Screen Shot 2022-01-12 at 2 33 06 am](https://user-images.githubusercontent.com/65474495/148972534-f903272f-2e59-44bb-8ce6-e8cdeeea6a37.png)


# Solution
Use mkdir to create a directory and change to this directory to later download those two file using wget, to the same directory as required
> <img width="175" alt="Screen Shot 2022-01-12 at 2 35 40 am" src="https://user-images.githubusercontent.com/65474495/148972953-0912869e-d532-432b-805c-3d511ce55493.png">

> <img width="439" alt="Screen Shot 2022-01-12 at 2 36 39 am" src="https://user-images.githubusercontent.com/65474495/148973129-42975132-70d5-4127-9a6d-cddec34ff30c.png">

> <img width="522" alt="Screen Shot 2022-01-12 at 2 36 48 am" src="https://user-images.githubusercontent.com/65474495/148973156-f946947e-e530-4efa-9d4f-1be141ca9237.png">

> <img width="258" alt="Screen Shot 2022-01-12 at 2 38 20 am" src="https://user-images.githubusercontent.com/65474495/148973414-faaaca8e-e92c-456d-922d-c34b2361eeab.png">


Use nano to read that password checker file in Python
> <img width="244" alt="Screen Shot 2022-01-12 at 2 39 04 am" src="https://user-images.githubusercontent.com/65474495/148973552-637d1c12-d4ed-4f54-9551-3594b79f474b.png">

These "chr(0x34), etc" looks like they are in hexademical, so I use this [website](https://www.rapidtables.com/convert/number/ascii-hex-bin-dec-converter.html) to convert those hex to [ASCII](https://en.wikipedia.org/wiki/ASCII), which gives the password to get the flag.
> <img width="556" alt="Screen Shot 2022-01-12 at 2 40 48 am" src="https://user-images.githubusercontent.com/65474495/148973856-81a04d81-5949-4d96-b604-1b565f7069f8.png">

> ![Screen Shot 2022-01-12 at 2 41 43 am](https://user-images.githubusercontent.com/65474495/148974042-eca4d38c-03cc-475a-bf56-ba2178aec5b7.png)

The password to get the flag is 4ec9, run level2.py to get the flag
> <img width="370" alt="Screen Shot 2022-01-12 at 2 43 32 am" src="https://user-images.githubusercontent.com/65474495/148974336-d4189761-2847-4a2f-bbfd-b44036ec0706.png">

## Flag
> picoCTF{tr45h_51ng1ng_9701e681}
