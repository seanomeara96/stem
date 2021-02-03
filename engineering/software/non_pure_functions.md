in addition to returning a value applying a non-pure function can generate side effects which make some chane to the interpreter or the computer

useless
```python
def square(x):
	mul(x, x) # Watch out! This call doesn't return a value.
```
usefull
```python
def square(x):
	print(mul(x,x))
```
[[software]]