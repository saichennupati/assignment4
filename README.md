# assignment4
x=int(input("What is your planned budget for this month?"))
expense= int(input("What is your expense on a primary thing?"))

while expense < x:
    other=int(input("You are still under budget, what about others?"))
    expense=other+expense
    total=expense
if total ==x:
    print("You are correctly on the budget!")
#elif total<=x:
    #print("You are under budget!")
elif total >=x:
    print("You are over budget!")
    
