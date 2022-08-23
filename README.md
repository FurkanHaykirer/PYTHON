# PYTHON
PYTHON Patika.com

Python Temel Proje 
1.Soru

l = [[1,'a',['cat'],2],[[[3]],'dog'],4,5]
lflat = []
def flat(n):
    for i in n:
        if isinstance(i, list):
            flat(i)
        else:
            lflat.append(i)
    return lnew
flat(l)
print(lflat)



2.Soru
l =[[1, 2], [3, 4], [5, 6, 7]]

for i in range(len(l)):
    l=l[::-1]
    l[i]=l[i][::-1]
print(l)

https://app.patika.dev/furkanhaykirer
