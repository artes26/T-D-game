
import random

names = ["xyz", "lmnt", "xyy", "abcd", "try",]


x=random.choice(names)
y=random.choice(names)
print(x, "turn")

ar=open("MyFile.txt","r")
ar1=ar.readlines()

x1=random.choice(ar1)


ar.close()

sss