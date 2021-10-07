# pallindromnumber
a=input()
b=""
for i in range(-1,-len(a)-1,-1):
	b=b+a[i]
if b==a:
	print("pallindrom")
elif a<b:
	print("no"
