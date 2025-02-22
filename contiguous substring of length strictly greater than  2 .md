def jana(s):
    vowels=set('aeiou')
    for i in range(len(s)-2):
        if s[i] in vowels and s[i+1] in vowels and s[i+2] in vowels:
            return "HAPPY"
    return "SAD"
t = int(input())
while t>0:
    s = input()
    re=jana(s)
    print(re)
    t-=1

'''''''
    input: 4
    s=aeiousad
    abxy
    aebcdefghij
    janatthanan
    output:"happy"
           "sad"
           "sad"
           "happy"
           "sad"
'''''''
