# How to use

### Just add the import at the top of your project:

```python
import namesimple_py
```

# Simple-py Commands
```python
import namesimple_py

say(shows your text like "Hello World!")

wait(2.5 <- type seconds for delay)

cls() <- clears terminal

type(you can type the text in terminal works like "Password: " ends with Enter)

hidetype(just like type but you can´t see what do you writing) 

createtkinter(             <- creates file with window version
("button", "Click me"),           <- you can add there button with Text like Click Me
("button", "Hello"),
("label", "Welcome!")             <- it generates text label with Welcome
)

pause() <- just adds pause

exit_program() <- just ends python

line(40) <- shows - in line type amount

repeat(4 <- how many times to repeat and the function -> say("Hello World!"))

openurl("https://example.com") <- opens url don't forget about http:// or https://
```

### ⚠️ Important: `repeat()`

Make sure to separate the number of repetitions and the function with a comma.

❌ Incorrect:

```python
repeat(4say("Hello World!"))
```

✅ Correct:

```python
repeat(4, say("Hello World!"))
```
You can also import several helpers:

```python
from namesimple_py import wait, say, cls, type, hidetype, line, pause, exit_program, createtkinter, repeat, openurl
```
