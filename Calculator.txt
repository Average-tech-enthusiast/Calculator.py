i = float(input("> "))

while True:
 x = input("+; -; *; /; c; e > ")
 
 if x=="+":
  o = float(input("> "))
  a = float(i+o)
  print("\n",i, "+", o, "=", a, "\n")
  i = a
 
 elif x=="-":
  o = float(input("> "))
  s = float(i-o)
  print("\n",i, "-", o, "=", s, "\n")
  i = s
 
 elif x=="*":
  o = float(input("> "))
  m = float(i*o)
  print("\n",i, "*", o, "=", m, "\n")
  i = m
 
 elif x=="/":
  o = float(input("> "))
  if i==0 and o==0:
   print("\n 0/0 = Error ಠ_ಠ\n")
   break
  elif o==0:
   print("\n Division not possible\n")
   break
  else:
   d = float(i/o)
   print("\n",i, "/", o, "=", d, "\n")
   i = d
 
 elif x=="c" or x=="C":
  k = input("Clear? [y/n]: ")
  if k == "y" or k=="Y":
   i = float(input("> "))
  else:
   continue
 elif x=="e" or x=="E":
  j = input("Exit? [y/n]: ")
  if j == "y" or j=="Y":
   break
  else:
   continue

#end of THE CODE   