t = int(input())

while t > 0:
    n = int(input())
    s = input()
    # Your code goes here
    Alice=0
    Bob=0
    server="A"
    for i in range(n):
        if  s[i]==server:
            if server=="A":
              Alice+=1
            else:
              Bob+=1
        else:
            if server=="A":
              server="B"
            else:
                server="A"
    print(Alice, Bob)
    t -= 1
  ''''''
  input:4
3
AAA
4
BBBB
5
ABABB
5
BABAB
outputs:
3 0
0 3
1 1
0 0
'''''''''

