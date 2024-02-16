# equal-parts-of-watermellon in python
#approach-1
n = int(input())
if n>2 and n%2 == 0:
  print("Yes")
else:
  print("No")

#approach-2
n = int(input())
if n>2:
  if n%2 == 0:
    print("Yes")
  else:
    print("No")
else:
  print("No")
