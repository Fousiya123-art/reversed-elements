n=[10,20,30,40,50] 
rev=[] 
for i in range(len(n),0,-1):   
  rev.append(n[i-1]) 
print("original list is:",n)
print("reverse list is",rev)
