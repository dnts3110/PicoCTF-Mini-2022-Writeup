# Question
![Screen Shot 2022-01-12 at 2 16 04 am](https://user-images.githubusercontent.com/65474495/148969480-b7430c66-f40a-4e99-a389-7e9160d3fffd.png)

# Solution
Use nc to see what happen on nc saturn.picoctf.net 52026
> <img width="625" alt="Screen Shot 2022-01-12 at 2 19 07 am" src="https://user-images.githubusercontent.com/65474495/148970057-fcaa0441-2032-48fa-acba-6c54f40b829f.png">

These "chr(0x62)" looks like they are in hexademical, so I use this [website](https://www.rapidtables.com/convert/number/ascii-hex-bin-dec-converter.html) to convert those hex to [ASCII](https://en.wikipedia.org/wiki/ASCII), which gives the rest of the flag
> ![Screen Shot 2022-01-12 at 2 30 05 am](https://user-images.githubusercontent.com/65474495/148972003-04da595a-4431-447a-8dc9-7960c89a60a6.png)

## Flag
> picoCTF{gl17ch_m3_n07_becf3861}
