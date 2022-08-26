# proje4
a=[[1,'a',['cat'],2],[[[3]],'dog'],4,5]
m=[]
def fla(a):
  for x in a:
    if type(x)==list:
      fla(x)
    else:
      m.append(x)

fla(a)
print(m)
