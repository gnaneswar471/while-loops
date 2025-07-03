# while-loops
________________armstrong______________
num=int(input())
t=num
l=len(str(t))
sum,rem=0,0
while t>0:
    rem=t%10
    sum+=rem**l
    t//=10
if num==sum:print(num,"is armstrong number")
else:print(num,"is not an armstrong number")
_______________OUTPUT_______________________
153
153 is armstrong number
9474
9474 is armstrong number
_______________niven's_______________________
num=int(input())
t=num
l=len(str(num))
rem,sum=0,0
while num>0:
    rem=num%10
    sum+=rem
    num//=10
if t%sum==0:print(t,"is niven's number")
else:print(t,"is not niven's number")
_________________OUTPUT_______________________
 156
156 is niven's number
123
123 is not a niven's number
