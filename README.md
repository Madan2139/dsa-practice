# dsa-practice
#union and intersection


a=[10,20,30,40,50,110,120,130,140,155]
b=[60,70,80,90,100,110,120,130,140,150]
c=[]
for i  in range (len(a)):
  c.append(a[i])
print(c)

for i in range (len(b)):
  for j in range(len(a)):
    if(b[i]!=a[j]):
      c.append(b[i])
      break
print(c)
c.sort()
print(c)

d=[]
for i in range(len(a)):
  for j in range(len(b)):
    if(a[i]==b[j]):
      d.append(a[i])
      break                 
print(d)
d.sort()
print(d)

