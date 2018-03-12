# Awesome-easter-eggs

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of Easter eggs in every language you can think of!

## Contents

- [Languages](#languages)
  - [Python](#user-content-python)
  - [Go](#user-content-go)
- [Terminal](#terminal)
- [FAQs](#faqs)
- [License](#license)

## Languages

### Python

1. The Zen of Python  
   ```python 
    import this
    ```
    It will print the Zen of Python.
    
 2. XKCD Comics
    ```python
    import antigravity
    ```
    It will open your default browser, and open a [classic XKCD comic](https://xkcd.com/).

3. Hello World
   ```python
   import __hello__
   ```
   It will print `Hello World!`

4. April Fool
   ```python
   from __future__ import barry_as_FLUFL
   1<>2
   ```
   This April Fool joke was posted about Barry Warsaw.

5. C-Style braces instead of indentation
   ``` python
   from __future__ import braces
   ```

   This will give the following Output
   
   ``` python
   File "<stdin>", line 1
   SyntaxError: not a chance
   ```

### Go

1. Easter Egg in net package
   
   In `src/net/net.go`, we find this variable:
   ``` go
   // aLongTimeAgo is a non-zero time, far in the past, used for
   // immediate cancelation of dials.
   aLongTimeAgo = time.Unix(233431200, 0)
   ```
   This Unix timestamp converts to May 25, 1977 @ 6pm. The day Star Wars opened in theaters -- hence
   "a long time ago." Cute!
  
## Terminal

### ASCII drawings and cute jokes

1. Mysterious super cow power

   ```
   $ apt-get moo
                 (__) 
                 (oo) 
           /------\/ 
          / |    ||   
         *  /\---/\ 
            ~~   ~~   
   ..."Have you mooed today?"...
   ```
2. Daniel Burrows Easter Egg

   ```
   $ aptitude moo 
   There are no Easter Eggs in this program. 
   $ aptitude -v moo 
   There really are no Easter Eggs in this program. 
   $ aptitude -vv moo 
   Didn't I already tell you that there are no Easter Eggs in this program? 
   $ aptitude -vvv moo 
   Stop it! 
   $ aptitude -vvvv moo 
   Okay, okay, if I give you an Easter Egg, will you go away? 
   $ aptitude -vvvvv moo 
   All right, you win.

                               /----\
                       -------/      \
                      /               \
                     /                |
   -----------------/                  --------\
   ----------------------------------------------
   $ aptitude -vvvvvv moo 
   What is it? It's an elephant being eaten by a snake, of course.
   ```
   
## FAQs

### What is an Easter Egg?

An Easter egg is a hidden message or a joke particularly found in a computer program or a video game or in this case, a programming 
language!

### What is this list about?

This list is a curated list of all the easter eggs in every programming language in the world from C# to Brainf**k.

### How to contribute?

It's simple! You pull a request mentioning a little bit about your Easter Egg and :tada:! It's done!

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Dhruv Apte](http://github.com/the-ethan-hunt) has waived
all copyright and related or neighboring rights to this work.
