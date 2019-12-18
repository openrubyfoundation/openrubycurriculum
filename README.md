# openrubycurriculum
An open source curriculum for builders, for Rubyists by Rubyists

Do you have some ideas about what people should learn when they're just starting out with Ruby? Drop some here, it doesn't need to be anything formal; this is just a brainstorming doc as of now.

I'd like to see several tiers here eventually, let's start with absolute beginners.

1. Install Ruby
2. Hello World
It's a longstanding tradition in software that new programmers begin their
careers with the same bit of code: the 'hello world' program.
This program will print some variant of 'hello world' to the screen and
then exit. If you've installed Ruby correctly you should now have a new
command in your terminal (how to open terminal) called 'irb'.
Begin by typing `irb` into the terminal and hitting enter. If everything
is setup correctly you're now looking at a prompt that looks something
like this:
```
irb(main):001:0>
```
This is an "interactive shell". The shell bit refers to a text-based
user interface to the operating system. We call it interactive because
you're able to type commands and get back some output, rather than just
watching the shell stream back output on it's own.

In this case the name 'irb' stands for 'interactive ruby shell', so this
is a place where you can learn to write Ruby code by typing it in and
hitting enter to see the output.

In our case we'll start with a Ruby method (in Ruby commands are known as
methods) that will print some text we supply to the screen: the `puts` method.

The method name 'puts' is short for 'put string' and that's exactly what it
does: it prints a string to the screen. A string is a collection of characters
in between some single or double quotes. It can be a single character ('a'),
a word ('ruby') or an entire sentence ('I love Ruby').

In this case we're going to output the string 'Hello World!', as though your
computer were waking up for the first time and greeting the world.

We want to pass our string as an argument to the `puts` method. An argument
in software generally refers to any data you pass to a method.

So here's our first program, go ahead and type this into your
interactive Ruby shell now (don't copy and paste, it's easier to learn if you type the code in by hand):
```
puts "Hello World!"
```
When you hit enter you should see something like this:
```
Hello World!
=> nil
```

Congratulations! You're a programmer. 😁

3. The rest of the owl 🦉
