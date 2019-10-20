---
title: Hello World in Arkscript
layout: default
last-modified: 2018-12-31
featured-image: hello-world-in-python-featured-image.JPEG
tags: [arkscript, hello-world]
authors:
  - arjitg
---

Welcome to this originally first edition of the Hello World in Every Language
series where I plan to embark on a journey of coding language exploration. 
First up, how to implement Hello World in Python. 
-Its really easy. Let's just get into it

## How to Implement the Solution

-Here's how you erite "Hello world" in arkscript. 
I chose Python to start as it has probably the easiest and most readable 
Hello World implementation in the realm of programming languages:

```arkscript
(print "Hello world")
```
Now, let's understand how it works, basically arkscript
And, we’re done. In fact, we don’t even have to compile anything. If we’re in 
the interpreter, we’ll print right away. Otherwise, we can easily call the 
script from the command line to get our result.

As you can probably imagine, this code works because Python has a built-in 
function called *print*. By passing that function a string, the interpreter 
is able to call the Python libraries that make the print possible.[^1]

## How to Run Solution

If we want to run this program, we should probably download a copy of 
Hello World in Python. After that, we should make sure we have the 
[latest Python interpreter][1]. From there, we can simply run the following 
command in the terminal:

```console
python hello-world.py
```
Alternatively, we can copy the solution into an [online Python interpreter][2] 
and hit run.[^1]

---

#### References

[^1]: J. Grifski, “Hello World in Python,” The Renegade Coder, 15-Mar-2018. [Online]. Available: 
<https://therenegadecoder.com/code/hello-world-in-python/>. [Accessed: 31-Dec-2018].  

[1]: https://www.python.org/downloads/  
[2]: https://www.tutorialspoint.com/execute_python3_online.php  
