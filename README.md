''''
Problem Statement 1:
Write a Python program using function concept that maps list of words into a list of
integers representing the lengths of the corresponding words.
Hint: ​If a list [ ab,cde,erty] is passed on to the python function output should come as
[2,3,4]
Here 2,3 and 4 are the lengths of the words in the list.

Problem Statement 2:
Write a Python function which takes a character (i.e. a string of length 1) and returns
True if it is a vowel, False otherwise.
'''


# 2.5.1
l1=[]
def lenlist(l2):
    for x in l2:
        l1.append(len(x))
    return(l1)

lenlist ([ 'ab','cde','erty'])


# 2.5.2
v1 = ['a','e','i','o','u']
def vowchk(x):
    if len(x)!=1:
        print ('Give only one character between A-Z !')
    elif x.lower() in v1:
        print (x, "is a vowel")
    else:
        print(x, "is not a vowel")
    
vowchk("C")
