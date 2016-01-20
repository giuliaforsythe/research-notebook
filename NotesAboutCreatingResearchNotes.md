#Tacit bits of creating web facing github research notes

I followed Alex Galarza's video instructions but I missed the part about actually linking my notes. Will I mess everything up if I go back and follow the text directions? That's the idea of github right? Version control?

Okay, here I go!

Well first problem: I need to install [mkdocs](http://www.mkdocs.org/)

"MkDocs supports Python 2.6, 2.7, 3.3 and 3.4"

I'm running mac osx 10.9.5 and python 2.7.5 
If I'm running 2.7.5 is that the same as 2.7? Why doesn't it say 2.7.x?

When I try to see what version of pip:
---
 pip --version
-bash: pip: command not found
---

I'm not running pip. This site says I need to get pip by installing the latest 2.7.x version of Python.

In order to that, this site says I should install Xcode (I thought this was always installed but I don't know that for sure, it's worth a try)
https://hackercodex.com/guide/mac-osx-mavericks-10.9-configuration/

I did a weird command and lo another text editor - vim. I made a file to tell my computer to always use 64 bit for this python stuff. Whew, glad I took care of that!

Instructions didn't include how to exit vim, but yay google. escape, colon for the record

ok, Xcode installed that was easy enough. Onto homebrew. 

Aaaand failed to connect. Oh, because I had the domain name incorrect. Copy paste is your friend. Enter, enter password. And I have homebrew. "My system is ready to brew"

but I still don't have pip.
oh yeah, install python
and now I have pip!

sheesh, why was I doing this? right, mkdocs. ok, back to that

wooooohoooo! mkdocs installed but mkdocs help doesn't work (oh, that's a [known issue]("https://github.com/mkdocs/mkdocs/issues") no problem, mkdocs works

If you want the file to auto-load menu items based on .md files in your research notebook folder, skip the step where you write the pages: list because this prevents the auto-generation from happening.





