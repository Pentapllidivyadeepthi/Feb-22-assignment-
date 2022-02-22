# Feb-22-assignment-
n=int(input())
for i in range(1,n+1):
    for k in range (i,n):
        print (' ',end=' ')
    for j in range (1,i+1):
        print ('*',end='    ')
    print ()
for i in range (1,n):
    for k in range (1,i+1):
        print (' ',end=' ')
    for j in range (i,n):
        print('*',end='    ')
    print ()
