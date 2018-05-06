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
