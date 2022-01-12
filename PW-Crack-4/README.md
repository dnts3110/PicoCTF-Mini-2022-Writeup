# Question
![Screen Shot 2022-01-12 at 3 28 16 pm](https://user-images.githubusercontent.com/65474495/149063884-f5d6eb70-d626-4b44-b4da-da82d6f612c0.png)

# Solution
Looking at source code, it looked the same as the PW Crack 3's source code, the only difference was they gave us 100 strings to check which one is correct instead of 7
> <img width="577" alt="Screen Shot 2022-01-12 at 3 33 46 pm" src="https://user-images.githubusercontent.com/65474495/149064350-2d9b5964-233b-4fb7-a102-7e0063bd357b.png">

So know trying to input each of those strings will not be feasible. thus I edited the source code so that it will automatically try every input for us when the level4.py script run, this used a for loop to do that
> <img width="606" alt="Screen Shot 2022-01-12 at 4 19 13 pm" src="https://user-images.githubusercontent.com/65474495/149068485-a4d9f533-8a36-47ac-bca8-57f7db8a647b.png">
> <img width="598" alt="Screen Shot 2022-01-12 at 4 21 25 pm" src="https://user-images.githubusercontent.com/65474495/149068680-793b6f22-c1bb-45ba-b290-4a1601a27049.png">

#Flag
> picoCTF{fl45h_5pr1ng1ng_89490f2d}
