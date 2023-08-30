# library-small-project
elif statement in python:
#small project
"""
0    no fine    #library fine charge projuct
1-5   0.5
5-10  1
10-30 5
>30   membership cancelled.
"""
def library():
  name=input("your name:")
  days=int(input("Total days:"))
  if days==0:
    print("good no fine amount")
  elif days>=1 and days<6:
    print("your fine amount:",days*0.5,'Rupees')
  elif days>=6 and days<11:
    print("your fine amount:",days*1,'Rupees')
  elif days>=11 and days<=30:
    print("your fine amount:",days*5,'Rupees')
  else:
    print("your membership is cancelled")
