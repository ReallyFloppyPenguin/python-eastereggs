# Python Eastereggs

***

# this
```
>>> import this
import this
The Zen of Python, by Tim Peters

Beautiful is better than ugly.
Explicit is better than implicit.
Simple is better than complex.
Complex is better than complicated.
Flat is better than nested.
Sparse is better than dense.
Readability counts.
Special cases aren't special enough to break the rules.
Although practicality beats purity.
Errors should never pass silently.
Unless explicitly silenced.
In the face of ambiguity, refuse the temptation to guess.
There should be one-- and preferably only one --obvious way to do it.
Although that way may not be obvious at first unless you're Dutch.
Now is better than never.
Although never is often better than *right* now.
If the implementation is hard to explain, it's a bad idea.
If the implementation is easy to explain, it may be a good idea.
Namespaces are one honking great idea -- let's do more of those!
```
***

# help me!
```
>>> import types
>>> help(types.CodeType)
Help on class code in module builtins:

class code(object)
 |  ...
 |
 |  Create a code object.  Not for the faint of heart.
 |
...
```

***

# Hiya
```
>>> import __hello__
>>> __hello__.main()
Hello world!
```
***
# Hiya (again)
```
>>> import __phello__
>>> __phello__.main()
Hello world!
```
***
# No way!
```
>>> from __future__ import braces
File "<stdin>", line 1
SyntaxError: not a chance
```
***
# Wot?
```
>>> hash(-1)
-2
```
***
# Also Wot?
```
>>> hash(float('inf'))
314159
```
***
# Hmm 🤔
```
>>> from __future__ import _Feature
File "<stdin>", line 1
SyntaxError: future feature _Feature is not defined
```
### credit to `bzr` on stackoverflow for providing me with these easter eggs in his [answer](https://stackoverflow.com/a/62071049)
