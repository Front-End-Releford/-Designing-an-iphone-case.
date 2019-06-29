# -Designing-an-iphone-case.
#Designing an iphone case.
length = int(input("What is the length of the phone?: "))
width = int(input("What is the width of the phone?: "))
cost = int(input("What is the cost per inch of the phone?: "))

def iphoneCase_cost(l,w,c):
    iphoneCase_cost = ((l * w) / 3) * c
    print('The desgign of the iPhone case will amount to $',format(iphoneCase_cost, '.2f'))

iphoneCase_cost(length,width,cost)
