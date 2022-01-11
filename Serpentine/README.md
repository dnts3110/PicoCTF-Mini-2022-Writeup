# Question
![Screen Shot 2022-01-12 at 3 02 01 am](https://user-images.githubusercontent.com/65474495/148977610-1aa86f34-d693-4a38-bc18-e8d8d26e6908.png)

# Solution
Use wget to get this Python script
> <img width="623" alt="Screen Shot 2022-01-12 at 3 09 11 am" src="https://user-images.githubusercontent.com/65474495/148978817-da03174b-268d-4ef1-a1d0-67334d8f53fa.png">


When I tried to run this Python script, it recommended me to check the source code
> <img width="608" alt="Screen Shot 2022-01-12 at 3 10 13 am" src="https://user-images.githubusercontent.com/65474495/148978993-745c12f2-f842-41d4-9225-913ee53a4ccd.png">

Take a look at the source code, this part in the code looks like it can give us the flag, basically the flag is the result of the [XOR operation](https://en.wikipedia.org/wiki/Exclusive_or) between the variable "flag_enc" and the string "enkidu".
> <img width="685" alt="Screen Shot 2022-01-12 at 3 12 44 am" src="https://user-images.githubusercontent.com/65474495/148979438-87f451b5-9a9b-4521-8f32-27daa6284f0f.png">



## Flag
> picoCTF{} 
