### Python Data Types and variables ###
#### 1. Numeric Variable ####
python supports various numeric datatypes like int (integer), float(decimal).
python also has complex numbers which is represented using 'j'.
python provides module called "math" for mathematical functions.

Example code snippet :
python math.sqrt(9)    # returns square root of 9 i.e. 3

#### 2. String Variable ####
String can be defined using single quotes(' ') or double quotes(" ").
We can access individual characters of string using indexing.
slicing is done by passing start index and end index separated by colon(:) inside brackets [].
we can concatenate strings using + operator.
strings are immutable so we cannot change them directly but we can use methods provided by python to manipulate them.
strings are immutable so we cannot change them   directly but we can use methods provided by python to manipulate them.

Example Code Snippet :  
str = "Hello World!"        
s = "Hello"                   # defining a string
print(type(s))                # prints <class 'str'>        

print(s[0])                  
print(s[1:5])               #        prints Hello               
print(s[:5] )                               
print(len(s))                # prints length


#### 3. List Variable ####
List is collection of items that are ordered and change 