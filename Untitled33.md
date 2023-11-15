ISLOWER():


```python
def strislower(string):
    '''
    islower() method checks if all characters in the string are lowercase.
    This method returns True if all alphabets in a string are lowercase alphabets.
    If the string contains at least one uppercase alphabet, it returns False.

    '''
    for i in string:
        asciicode = ord(i)
    if  asciicode in range(97,125):
            print("True")
    else:
            print("False")
```


```python
strislower('sruthi')
```

    True
    


```python
strislower('SRUTHI')
```

    False
    

ISNUMERIC():


```python
def strisnumeric(string):
    '''
   isnumeric() method is used to determine whether the string consists of numeric characters or not.
   It returns a Boolean value.
   If all characters in the string are numeric and it is not empty, it returns “True”
   If all characters in the string are numeric characters, otherwise returns “False”.
   isnumeric() does not take any parameters

    '''
    for num in string:
        asciicode = ord(num)
    if asciicode in range(48,58) or asciicode==46:
        print('True')
    else:
        print('False')
```


```python
strisnumeric("2,3,4")
```

    True
    

ISALNUM():




```python
def strisalnum(string):
    '''
     isalnum() = method checks whether all the characters in a given string are either alphabet or
     numeric (alphanumeric) characters.
     isalnum() method takes no parameters.
    '''
    for i in string:
        asciicode = ord(i)
    if  asciicode in (range(97,123) and range(48,58)):
            print(True)
    else:
            print(False)
```


```python
strisalnum("string123")
```

    True
    

isalpha():


```python
def strisalpha(string):
    '''
    isalpha() method is used to check whether all characters in the String are an alphabet.
    isalpha() does not take any parameters.
    '''
    for i in string:
        asciicode = ord(i)
    if  asciicode in (range(65,91) or range(97,123)):
          print(True)
    else:
          print(False)
```


```python
strisalpha('PYTHON')
```

    True
    

isascii():


```python
def strisascii(string):
    '''
    isascii() method checks if all characters in a given Python string are ASCII characters.
    If they are, it returns True; otherwise, it returns False.
    The Python string isascii method doesn’t accept any parameters.'''
    for i in string:
        asciicode = ord(i)
    if  ord(i)<128:
          print(True)
    else:
          print(False)
```


```python
strisascii('hello world')
```

    True
    

isdecimal():


```python
def strisdecimal(string):
    '''
    isdecimal() function returns true if all characters in a string are decimal, else it returns False.
    string_name is the string whose characters are to be checked
    This method does not takes any parameters .
    '''
    for char in string:
        asciicode = ord(char)
        if not (48 <= asciicode <= 58):
            print('false')
            return
    print('true')
```


```python
strisdecimal('1234')
```

    true
    

isdigit():


```python
def strisdigit(string):
    '''
    isdigit() method returns “True” if all characters in the string are digits, Otherwise, It returns “False”. 
    isdigit() does not take any parameters'''
    for i in string:
        asciicode = ord(i)
    if  48 <= asciicode <=58:
          print(True)
    else:
          print(False)
```


```python
strisdigit("123")
```

    True
    

isidentifier():


```python
def strisidentifier(string):
    '''
    isidentifier() method is used to check whether a string is a valid identifier or not.
    The method returns True if the string is a valid identifier, else returns False.
    The method does not take any parameters.
    '''
    for i in string:
        asciicode = ord(i)
    if  not 48 <= asciicode <=58:
          print(True)
    else:
          print(False)
        
```


```python
strisidentifier('abc')
```

    True
    


```python
strisidentifier('123')
```

    False
    


```python

```
