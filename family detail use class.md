class jana:
    def famely(self,name,age):
        self.name = name
        self.age = age
    def sister(self):
        print("this my 1st systere", self.name)
        print("shes age is", self.age)
    def ssister(self):
        print("she is my second syster" ,self.name)
        print("she is age is ", self.age)
    def brother(self):
        print("he is mt bro", self.name)
        print("he is age is", self.age)
p1 = jana()
p2 = jana()
p3 = jana()
p1.famely("rani",30)
p1.sister()
p2.famely("gayathri",23)
p2.ssister()
p3.famely("vasanthan",21)
p3.brother()
-----------------------------
output
this my 1st systere rani
shes age is 30
she is my second syster gayathri
she is age is  23
he is mt bro vasanthan
he is age is 21
-----------------------
