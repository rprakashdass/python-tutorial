# Class and objects intro
1. With self
```
class addd:
    def __init__(self,a,b):
        self.a = a
        self.b = b
    def res(self):
        res = self.a + self.b
        return res

print(addd(9,4).res())
```
# or
2.without self
```
class addd:
    def __init__(c,a,b):
        c.a = a
        c.b = b
    def res(c):
        res = c.a + c.b
        return res

print(addd(a,b).res())
```
