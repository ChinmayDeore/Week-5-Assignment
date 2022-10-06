## Chinmay D. 9/21/2022
def CmsRequest():
# Naming and starting the function
    first = "chinmay"
# [1] Stores first name as variable
    last = "DEORE"
# [2] Stores last name as variable
    print("Hello,",first.upper(),last.lower())
# [3] Prints out a statement converting first name to upper case and last name to lowercase
    print("\n\n")
# [4] Prints out 2 seperate blank lines
    name = first+" "+last
# [5] Stores both parts of my name as one fullname variable      
    print(name[name.index(' ')+1:])
# [6] Slices last name from full name and prints it out on one line
    name = name[:name.index(' ')+1]+last+", Walsh College Student"
    print(name)
# [7] Prints out a new statement containing last name in the beginning
    print('''"Start by doing what\'s necessary; then do what\'s possible;
     and suddenly you are doing the impossible - Francis of Assisi"''')
# [8] Prints out the given statement in the expected spacing format
    x = 6.9
    y = 42.0
# [9] Stores 2 decimal numbers as variables
    sum = x + y
    subtract = x-y
    product = x*y
    divide = x/y
# [10] Stores the sum, difference, product and division of x & y as variables
    print(str(x)+" plus "+str(y)+" equals "+str(sum))
    print(x,"minus",y,"equals",subtract)
    print("The product of {} & {} is {}".format(x,y,product))
    print(f"{x} divided by {y} equals {divide}")
# [11] Prints out all the stored information using concentation, string formatting expressions, 
# string formatting method calls, and f-Strings
    sqrt = round(product**(1/2),2)
    print(f"The square root of {product} equals {sqrt:.2f}")
# [12] Create and stores the square root of the product as a variable and prints it out.
    date = 5
    month = "October"
# [13] Stores today's date (day and month) as 2 different variables
    print("\t\tToday is day %d of the month of %s." % (date,month))
# [14] Tabs the sentence two times before printing a statement including date as output
CmsRequest() 
# Calls the function and ends the program