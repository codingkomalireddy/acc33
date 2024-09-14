def check(s,t):
    if sorted(s)==sorted(t):
        return("True")
    else:
        return("False")
s=input()
t=input()
print(check(s,t))
