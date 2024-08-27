# evall
string=input("please enter string: ")
uppercase_char=set()
lowercase_char=set()
for char in string:
    if char.isupper():
        uppercase_char.add(char)
    elif char.islower():
        lowercase_char.add(char)
    else:
        print("invalid text")
sorted_upper=sorted(uppercase_char)
sorted_lower=sorted(lowercase_char)
print("uppercase letters are: ",sorted_upper)
print("lowercase letters are: ",sorted_lower)
