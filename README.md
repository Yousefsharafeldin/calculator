x=float(input("enter your num1="))
i=input("enter the operator :")
y=float(input("enter your num2="))
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
                              def factorial(x):
			           if x>0 and i =="!":
				       return x*factorial(x-1)
				   else:
				       return 1
print(factorial(x))
