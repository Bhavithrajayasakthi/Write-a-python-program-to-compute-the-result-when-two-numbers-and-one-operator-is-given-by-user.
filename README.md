# Write-a-python-program-to-compute-the-result-when-two-numbers-and-one-operator-is-given-by-user.
a=int(input("enter 1st number:"))
b=int(input("enter 2nd number:"))
c=input("enter the operation +,-,/,*:")
print("the result is:",end='')
if c=='+':
    print(a+b)
elif c=='-':
    print(a-b)
elif c=='/':
    print(a/b)
elif c=='*':
    print(a*b)
else:
     print ("error:wrong operator entered")   

Output 1:
enter 1st number:15
enter 2nd number:20
enter the operation +,-,/,*:/
the result is:0.75

Output 2:
enter 1st number:10
enter 2nd number:13
enter the operation +,-,/,*:%
the result is:error:wrong operator entered

