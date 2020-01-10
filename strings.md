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

    