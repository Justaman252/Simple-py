# How to use

### Just add the import and install:

```bash
pip install namesimple-py
```

```python
import namesimple_py
```

# Simple-py Commands
```python
import namesimple_py

n.say(shows your text like "Hello World!")

n.wait(2.5 <- type seconds for delay)

n.cls() <- clears terminal

n.type(you can type the text in terminal works like "Password: " ends with Enter)

n.hidetype(just like type but you can´t see what do you writing) 

n.pause() <- just adds pause

n.exit_program() <- just ends python

n.line(40) <- shows - in line type amount

n.repeat(4 <- how many times to repeat and the function -> say("Hello World!"))

n.openurl("https://example.com") <- opens url don't forget about http:// or https://
```

### ⚠️ Important: `repeat()`

Make sure to separate the number of repetitions and the function with a comma.

❌ Incorrect:

```python
n.repeat(4say("Hello World!"))
```

✅ Correct:

```python
n.repeat(4, say("Hello World!"))
```

