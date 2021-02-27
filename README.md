# palidrom
#program to find palidram
def p(num):
    x=num[::-1]
    if x==num:
        print ("palidram")
    else:
        print ("not palidram")

print (p("madam"))    
