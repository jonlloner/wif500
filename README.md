# Challenge WIF 500
![20220413_164254](https://user-images.githubusercontent.com/82582647/163194722-6d8156b7-fbc9-403d-98f9-a9cde77bc499.jpg) </br>
**Find the key, get 100 BTC donations!**</br>

Run ```wif500.exe -range 1``` (1-3364)

The known part of the key is 40 characters from 52</br>
A large range of 12 characters is divided into 3364 small ranges</br>
The address [1PfNh5fRcE9JKDmicD2Rh3pexGwce1LqyU](https://www.blockchain.com/btc/address/1PfNh5fRcE9JKDmicD2Rh3pexGwce1LqyU)</br>
Passed (blank) ranges [**HERE**](https://github.com/phrutis/wif500/blob/main/x64/Release/Passed-ranges.md)

### Frequently asked Questions:

WIF real?</br>
To find out, you need to go through a large range and find out.</br>
This requires large GPU resources.</br>

Why is the program without source codes?</br>
The correct ranges and other parameters are sewn into the WifSolverCuda program.</br>
Knowing them, the user can find the key on his own and take everything for himself.</br>

Why did you paint over the characters in the photo?</br>
So that the user does not look for the key on the original program.</br>

Does the program require an internet connection?</br>
No, the program is looking for the key offline.</br>

If I find the key can I take all the coins for myself?</br>
No, you will find the encrypted key.</br>
Only the organizers of the challenge can decrypt this key and pay you a donation.</br>

There is a video in which there is a similar key.</br>
There are errors in the video that make the key impossible to find.</br>

I have many GPUs. How to start?</br>
Run each GPU separately with a new range Add your card id -d ?</br>
Example:</br>
```wif500.exe -range 1000 -d 0```</br>
```wif500.exe -range 1001 -d 1```</br>
```wif500.exe -range 1002 -d 2```</br>

How long can you go through the range?</br>
RTX 3090 4 Gkey/s = ~4 days.</br>
RTX 3060 2 Gkey/s = ~8 days.</br>

If you have any questions, ask them [here](https://github.com/phrutis/wif500/issues)
