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
-Can declare variables without types using None 

# Files 
- can set variables to open files
- myfile = open('myfile.txt')
- see text with .read()
- .seek(0) resets the cursor
- .readlines() reads file and seperates by line
- python follows local filepaths 
- can open and assign variables to files with following syntax: 

with open ("myfile.txt") as my_new_file: 
    contents = my_new_file.read()

- writing syntax: 

with open ("myfile.txt", mode = 'w') as my_new_file: 
    contents = my_new_file.write()

-Several modes for different file type operations 
- r = read 
- w = write 
- a = append 
- r+ = reading and writing 
- w+ = writing and reading, overwrites existing file or creates a new file 

# Comparison Operators 
- All return boolean 
- Types work 
- floats and ints will return true is 3.0 === 3 returns true 
- standards > and < operators including <= >=
- uses 'and' 'or' 

# Statements 
- uses if elif and else syntax
