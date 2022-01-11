# Question
![Screen Shot 2022-01-11 at 9 31 07 pm](https://user-images.githubusercontent.com/65474495/148927099-2c2ce454-6d40-431f-9a58-6da415042485.png)
# Solution
Use [wget](https://www.gnu.org/software/wget/manual/wget.html) to get the given Python script 
> <img width="462" alt="Screen Shot 2022-01-11 at 10 02 44 pm" src="https://user-images.githubusercontent.com/65474495/148931196-7bf01667-687f-4773-bc86-04fe085d81a8.png">

Then it should stored at the directory you are at, use "ls" to check 
> <img width="539" alt="Screen Shot 2022-01-11 at 10 03 27 pm" src="https://user-images.githubusercontent.com/65474495/148931295-2d4bebcd-f653-4496-8274-f8d0e758fb58.png">

Run the Python file to see what it requires
> <img width="427" alt="Screen Shot 2022-01-11 at 10 04 14 pm" src="https://user-images.githubusercontent.com/65474495/148931393-15e58a8c-858e-4134-8eda-99d1f2133f19.png">

It requires us to convert a number from decimal base to binary base, so I use this website called CyberChef(https://gchq.github.io/CyberChef/) to help me do this
> ![Screen Shot 2022-01-11 at 10 43 09 pm](https://user-images.githubusercontent.com/65474495/148936724-fd7a3d13-fe5d-48b6-846f-99b57cb619ef.png)

Now I know the answer of this Python script, lets input this and take the flag :)
> <img width="544" alt="Screen Shot 2022-01-11 at 10 44 57 pm" src="https://user-images.githubusercontent.com/65474495/148936945-f0b58315-2dcc-462d-8d89-b8bb9a70650e.png">

## Flag
> picoCTF{4ll_y0ur_b4535_e2a58836}

## NOTE
I strongly recommend everyone new to CTF to use [CyberChef](https://gchq.github.io/CyberChef/) as it is easy to use and it has graphical interface. In the beginning I think this will be helpful, along the way you can find some nice software on github that can be used inside Kali Linux or something like that.
I found this websire while participating in MetaCTF, which is my first CTF and also my first ever documenting a [writeup](https://github.com/dnts3110/MetaCTF-2021-Write-up) for a CTF.
