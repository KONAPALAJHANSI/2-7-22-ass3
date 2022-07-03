def is_prime(n):
  for i in range(2,n):
    if (n%i) == 0:
      return False
  return True
l=list(map(int,input().split()))
n=len(l)
for i in range (0,n):
    a=is_prime(l[i])
    if a:
        print(i)
