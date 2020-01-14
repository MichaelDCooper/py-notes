# Strings
Strings can use either double or single quotes 

Index strings the same as arrays: "Hello"[0] = 'H'

Index strings in reverse "Hello"[-1] = "o"

Slice segment of strings "Hello"[1:3] = "el"

Reverse strings "Hello"[::-1] = "olleH" 

Set slice interval "Hello"[::2] = "Hlo"

Strings are immutable concat works as follows: 
    - my_string = "fun" 
    - my_string[0] = 's' NOT ALLOWED
    -new_ending = my_string[1:]
    -final_string = "f" + new_ending

Access internal methods using . ie my_string.upper()

String interpolation: 
print('Hello {}'.format('World))

prints Hello World

# Lists: 
my_List = [1,2,3,4]

string_List = ['h','i','j','k']

mixed_list = = ['h',2,3,4]

Has built in functions, pop, append, sort, and reverse. 

-pop can take an index pop(2)
-sort sorts in place does not return anything

# Dictionaries

-Are JS objects. 
-Cannot be sorted 

-access keys/values with .keys()/.values()

# Tuples

-Immutable 
- Few Functions 
- (2,3,4,5)

# Sets

- unordered collections of unique objects 
- use add() to add into set. 

# Bools 

-True and False 
-Have types 
- Are returned from comparison operators 
