**Title:** Binary Search

**Difficulty:** Easy

**Summary (TL;DR):**

Using the Art of Binary Search to guess the correct number.

**1. Scope & Setup**

**Target:** ctf-player@atlas.picoctf.net @ 49250

**Environment:** Local System / PicoCTF VM

**Tools used:** Terminal, Browser

**2. Recon**

>**What is Binary Search?**
>
>Binary Search is an efficient algorithm that finds an element in a **sorted list** by
>repeatedly dividing the search range in half until the element is found (or not).

**3. Exploit** 

Using a terminal or webshell, connect to the server with ```ssh -p 49250 ctf-player@atlas.picoctf.net``` .
Using password ```6abf4a82```.

Now the program will ask you to choose a number b/w 1 an 1000.

**Note that you only have 10 chances.**

Using Binary search and the higher/lower response from server, guess untill you get the answer. 

It might take a few re-connects according to your luck, but its fairly easy. I beleive in you.

**4. Flag**

```picoCTF{g00d_gu355_bee04a2a}```

**5. References/Credits**

[Binary Search in 100 seconds](https://www.youtube.com/watch?v=MFhxShGxHWc)

