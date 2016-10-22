# pythonprogram of swap and reverse of input number
n=int(input("enter a number"))
reverseno=0
while n>0:
    reminder=n%10
    reverseno=(reverseno+10)*reminder
    n=n//10
print("reverse of input number",reverseno)


