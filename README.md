x=float(input("enter your num1="))
y=float(input("enter your num2="))
i=input("enter the operator :")
if i=="+":
    sumition= x+y
    print("result= ",sumition)
else :
      if i=='-' and x>y:
          sups=x-y
          print("result= ",sups)
      else:
          if i=='+/':
              avr=sumition/2
              print("result= ",avr)
          else:
              if i=='/' and x>y:
                  divid=x/y
                  print("result= ",divid)
              else:
                  if i=='*':
                      multiply=x*y
                      print("result= ",multiply)
                  else:
                      if i=='^':
                          power= x**y
                          print("result= ",power)
                      else:
                          if i =='//':
                              reminder=x//y
                              print("result= ",  reminder)
                          else:
                              print("CAN'T SOLVE IT")
