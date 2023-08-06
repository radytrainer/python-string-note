## String in Python Note

### 1.  String value 
String is a collection of alphabets, words or other characters. String represent in double quote `" "` or single quote `' '`

<i>Example: </i>
- [x] firstName = "Rady"
- [x] lastName = "Y"
- [x] schoolName = 'PNC'
- [x] studentName = 'Bopha'
- [x] text = "Hello world in 1995"

#### String conversion
> Convert integer, float and boolean to string

- [x] floatNumber = 10.5 :arrow_right: string = str(floatNumber) `// "10.5"`
- [x] number = 10 :arrow_right: string = str(number) `// "10"`
- [x] isBoolean = True :arrow_right: string = string(isBoolean) `// "True"`
- [x] isBoolean = False :arrow_right: string = string(isBoolean) `// "False"`

### 2. Input in Python

- [x] string = input()
- [x] string = str(input())
- [x] number = int(input())
- [x] number = float(input())

### 3. Output in Python
- [x] print("Hello world")
- [x] print(100)
- [x] print(10.5)
- [x] print(True)
- [x] number = 10 :arrow_right: print(number)
- [x] string = 'rady' :arrow_right: print(string)
- [x] number = 10.5 :arrow_right: print(number)
- [x] hasNumber = False :arrow_right: print(hasNumber)

### 4. String accessability in Python
To access a string we use `[]` sign and `index` of each character starting from `0`
- [x] text = "ABC" :arrow_right: text[0] `// A`
- [x] text = "ABC" :arrow_right: text[1] `// B`
- [x] text = "ABC" :arrow_right: text[2] `// C`
- [x] text = "ABC" :arrow_right: text[3] `// IndexError: string index out of range`

### 5. String function in Python
- [x] string = "abc" :arrow_right: len(string) `// 3`
- [x] string = "abc" :arrow_right: string.upper() `// ABC`
- [x] string = "aBc" :arrow_right: string.lower() `// abc`
- [x] string = "abc" :arrow_right: string.isupper() `// False`
- [x] string = "abc" :arrow_right: string.isLower() `// True`
- [x] string = "abc" :arrow_right: string.isnumeric() `// False`
- [x] string = "12" :arrow_right: string.isnumeric() `// True`
- [x] number = 12 :arrow_right: str(number) `// "12"`

### 6. String concatination
- [x] string = "A" + "B" `// AB`
- [x] string = "5" + "6" `// 56`
- [x] string = 10 + "7" `// TypeError: unsupported operand type(s) for +: 'int' and 'str'`
- [x] string = 5.6 + "A" `// TypeError: unsupported operand type(s) for +: 'float' and 'str'`
- [x] string = str(100) + "8" `// 1008`

### 7. String looping
For loop iteration by default incrementing from `0` it th same index of string
```
text = "abc"
for i in range(len(text)):
    print(text[i])
```
`Output of code above:`
```
a
b
c
```

#### Other ways to loop
```
text = "abc"
i = 0
while i < len(text):
    print(text[i])
    i = i + 1
```
`Output of code above:`
```
a
b
c
```