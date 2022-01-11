# Question
![Screen Shot 2022-01-12 at 2 48 05 am](https://user-images.githubusercontent.com/65474495/148975056-afc0ff1b-0d0b-4ebd-9f68-012bf6ddd739.png)

# Solution
Use nc to see what happen on nc saturn.picoctf.net 65352
> <img width="585" alt="Screen Shot 2022-01-12 at 2 49 49 am" src="https://user-images.githubusercontent.com/65474495/148975426-33aa9de4-b699-40e2-8d91-9516d43a26ea.png">

It requires us to md5 hash the text "babies", so I use this website called CyberChef(https://gchq.github.io/CyberChef/), which give this result
> ![Screen Shot 2022-01-12 at 2 52 46 am](https://user-images.githubusercontent.com/65474495/148976014-7eebbc7f-3bdc-4de9-843c-7f7dc5ef1160.png)

> 8374d0764f1466e601c624254222ad53

Lets input this and see what happens
> <img width="625" alt="Screen Shot 2022-01-12 at 2 53 56 am" src="https://user-images.githubusercontent.com/65474495/148976188-054f7476-866e-4e64-b6ff-e45a6fbeb58f.png">
> So it seems like there is a timeout mechanic and it will random the text that is required to be hashed, :) so lets do everything above quickly and see if we can get the flag.

Do everything above for a second time, but quickly and see what happens
> <img width="625" alt="Screen Shot 2022-01-12 at 2 57 26 am" src="https://user-images.githubusercontent.com/65474495/148976769-31cdf24b-fe4f-4d97-b0fb-d1fbb058a9fa.png">

Interestingly, it requires us to do the md5 hash function for 3 times quickly before getting the flag

## Flag
> picoCTF{4ppl1c4710n_r3c31v3d_674c1de2}

