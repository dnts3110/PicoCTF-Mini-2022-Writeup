# Question
![Screen Shot 2022-01-12 at 4 22 44 pm](https://user-images.githubusercontent.com/65474495/149068786-15771f88-ba28-43b5-b798-4b5db4021a55.png)


# Solution
Looking at source code, it looked the same as the PW Crack 4's source code, the only difference was they gave us a txt file, which has a lot of strings, to check which one is correct instead of 100
> <img width="577" alt="Screen Shot 2022-01-12 at 3 33 46 pm" src="https://user-images.githubusercontent.com/65474495/149064350-2d9b5964-233b-4fb7-a102-7e0063bd357b.png">

So now besides using a for loop to automatically try every input for us when the level4.py script run, we also need to edit the code so that it will open and read that txt file appropriately, that is using open() to access these strings and strip() to trim the whitespace from them if any. 
> <img width="485" alt="Screen Shot 2022-01-12 at 4 36 10 pm" src="https://user-images.githubusercontent.com/65474495/149070007-50fdc67e-4464-403c-8167-097caad31624.png">
> <img width="533" alt="Screen Shot 2022-01-12 at 4 38 17 pm" src="https://user-images.githubusercontent.com/65474495/149070201-3693b557-3eb2-4b04-a9be-f75c6dd57f6c.png">

#Flag
> picoCTF{h45h_sl1ng1ng_2f021ce9}
