# basic_python

## First
For Python 2
```python
print 'hello'
```
For Python 3
```python
print('hello')
```

## Comment
```python
# print 'hello'
```

## Data type
Python is dynamic typed.
```python
x = 54
y = 5.4
s = 'hello'
b = True
```
```python
print 'x: {}'.format(x)
```
```python
print '{s} {x}'.format(s=s, x=x)
```
```python
print '{sakura} {xmen}'.format(sakura=s, xmen=x)
```

## List
```python
a = [1, 234, 45, 45]
b = ['hello', 'python']
```
```python
a[-1]
```
```python
a[0:2]
```
```python
s[0:4]
```
```python
a[1] = a[1] - 1
```
```python
b.append('world')
```
```python
len(a)
```
```python
a.count(456)
```
```python
234 in a
```

## Dictionary
```python
d = {'key': 'Value', 'last': 'Suzuki'}
```
```python
d['last']
```
```python
d['first'] = 'Alto'
```

## Tuple
```python
t = (100, 200)
```

## Control
```python
if x == 54:
    print 'yes'
elif x == 5.4:
    print 'no'
else:
    print 'NO'
```
```python
while x == 54:
    print 'yes'
```
```python
for item in a:
    print item
```

## Exception
```python
z += 1
```
```python
try:
    z += 1
except:
    z = 0
    z += 1
```

## Exercises
```python
# Replace space in a string with underscore
s = 'sublime text'
w = s.split()
s = '_'.join(w)
print s
```

```python
# Split string by symbol
s = '   this ;is;  so;  fun  '
w = s.split(';')
# ... and also cleanup the whitespaces
w = [r.strip() for r in s.split(';')]
```

```python
# Make a copy of the list without duplicated numbers
a = [1, 2, 3, 3, 5, 5, 6]
b = []
...
```

```python
# Count number of duplicate of each unique number in the list
a = [10, 10, 20, 20, 10, 20, 10, 30, 30, 40]

# Expected result: count = {10: 4, 20: 3, 30: 2, 40: 1}
```

## Read and write to file
```python
s = 'label_a,label_b,label_c'

with open('test.txt', 'w') as f:
    f.write(s + '\n')
```
```python
with open('text.txt', 'r') as f:
    for line in f:
        print line
```

