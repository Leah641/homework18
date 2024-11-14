# homework18

x=int(input("What is x:"))

def F(x):

    if x>=0 and x<=1:
    
        return("1")
    
    elif x>1:
    
        return(x*(x-1))
        
        F(x*(x-1))


print("F(x)="+str(F(x)))
