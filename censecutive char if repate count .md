for i in range(int(input())):
    n=int(input())
    s=input()
    c=0
    for j in range(len(s)-1):
        if s[j]==s[j+1]:
            c+=1
    print(c)
    """
    input:--3
    n=char leangth(5)
    s=char("11001")
    c=count (if char and char+1 is equal c=increse)
    output:--2
    '''
