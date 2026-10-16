#1
a=int(input())
b=int(input())
if a>b:
    print(a)
elif b>a:
    print(b)
else:
    print("numbers are equal")








#2
a=int(input())
if a>0:
    print("positive")
elif a==0:
    print("zero")
else:
    print('negative')







#3
a=int(input())
c=a%2
if c==0:
    print("cut")
else:
    print("tek")







#4
score=int(input())
if score>100:
    print('invalid score')
elif score>90:
    print('A')
elif 80<score<91:
    print("B")
elif 70<score<81:
    print("C")
elif 60<score<71:
    print("D")
elif 50<score<61:
    print("E")
elif 0<score<51:
    print("F")
else:
    print('invaled score')








#5
a=int(input())
b=int(input())
c=int(input())
if a>b and a>c:
    print(a)
elif b>a and b>c:
    print(b)
else:
    print(c)






#6
a = int(input('Enter first number: '))
b = int(input('Enter second number: '))
c = input('Write your operation (+, -, *, /, %, **, //): ')

match c:
    case '+':
        print(a + b)
    case '-':
        print(a - b)
    case '*':
        print(a * b)
    case '/':
        if b == 0:
            print('Error: Cannot divide by zero')
        else:
            print(a / b)
    case '%':
        if b == 0:
            print('Error: Cannot modulo by zero')
        else:
            print(a % b)
    case '//':
        if b == 0:
            print('Error: Cannot divide by zero')
        else:
            print(a // b)
    case '**':
        if a == 0 and b < 0:
            print('Error: 0 cannot be raised to a negative power')
        else:
            print(a ** b)
    case _:
        print('Invalid operation')








#7
a=int(input())
if a<0:
    print("Invalid age")
elif 0<=a<13:
      print("child")
elif 12<a<18:
      print("teenager")
elif 17<a<65:
      print("adult")
elif a>64:
      print("senior")










#8
a=int(input())
if a<100:
    c=0
elif 100<=a<300:
    c=a*0.1
elif 300<=a<500:
    c=a*0.15
elif a>=500:
    c=a*0.2
print("Original Price:",a,"AZN")
print("Discount Amount:",c)
print("Final Price:", a-c,"AZN")









#9
a = int(input())
b = int(input())
c = int(input())

if a <= b and a <= c:
    if b <= c:
        print(a, b, c)
    else:
        print(a, c, b)
elif b <= a and b <= c:
    if a <= c:
        print(b, a, c)
    else:
        print(b, c, a)
else:
    if a <= b:
        print(c, a, b)
    else:
        print(c, b, a)





#10
k=1000
a=int(input())
if a<=0:
    print("Invalid amount")
elif a>k:
    print("Insufficient balance")
else:
    print(k-a)








#11
k=int(input("write your monthly elecricity usage in kWh"))
if 0<=k<=100:
    print("Usage:",k,'kWh')
    print("Applied Rate:"0.08)
    print("Total Bill:",k*0.08)
elif 100<k<=300:
    print("Usage:",k,'kWh')
    print("Applied Rate:",0.12)
    print("Total Bill:",k*0.12)
elif 300<k:
    print("Usage:",k,'kWh')
    print("Applied Rate:",0.15)
    print("Total Bill:",k*0.15)
elif k<0:
    print('this usage is invalid')







#12
k=int(input("write your distance in km"))
c=2
if 0<k<=5:
    print("Distance:",k,'km')
    print("Starting Fee:", c, "AZN")
    print("Distance Fee:",k*0.70,"AZN")
    print("Total Fare:",k*0.70+c,'AZN')
elif 5<k<=15:
    print("Distance:",k,'km')
    print("Starting Fee:", c, "AZN")
    print("Distance Fee:",k*0.60,"AZN")
    print("Total Fare:",k*0.60+c,'AZN')
elif 15<k:
    print("Distance:",k,'km')
    print("Starting Fee:", c, "AZN")
    print("Distance Fee:",k*0.50,"AZN")
    print("Total Fare:",k*0.50+c,'AZN')
elif k<=0:
    print('this usage is invalid')








#13
a=int(input('wrie your age'))
b=int(input('wrie your monthly salary'))
c=int(input("write your requested loan amount."))
k=0
if a>0:
    if b>0:
        if c>0:
            k=1
        else:
            print('invalid input')
    else:
        print('invalid input')
else:
    print('invalid input')

if k==1:
    if a>=18:
        if b>=500:
            if c<=b*10:
                print('Approved')
            else:
                print('not approved')
        else:
            print('your monthly salary is below 500')
    else:
        print('your age is below 18')








#14
a=int(input())
b=int(input())
c=int(input())
k=0
if a>0 and b>0 and c>0:
    if a+b>c:
        if a+c>b:
            if b+c>a:
                k=1
            else:
                print('Triangle cannot be created')
        else:
            print('Triangle cannot be created')
    else:
        print('Triangle cannot be created')

if k==1:
    if a==b==c:
        print(' Equilateral')
    elif a!=b!=c!=a:
        print(' Scalene')
    else:
        print('Isosceles')








#15
a=int(input('exam score'))
b=int(input('school score'))
c=int(input('age'))
k=1
if not(c<16 and 0<=a<=700 and 0<=b<=100):
    print('check your answer')
    k=0
if k==1:
    if 600<=a<=700:
        print('scholarship')
    elif 450<=a<=599:
        print('accepted')
    elif 300<=a<=449:
        if b>=80:
            print('accepted')
        else:
            print('reject')
    else:
        print('reject')








#16
k=int(input('exam score'))
if k<0 or k>100:
    print('invalid score')
else:
    result = "Pass" if k >= 51 else "Fail"
    print(result)







#17
k=int(input('total order:'))
b=input(' membership answer:')
if k<0 or b!='yes' and b!='no':
    print('check your answer')
else:
    c= k if  k>=50 or b=='yes' else k+5 
    print(c, ' Delivery:', c-k)








#18
k=int(input())
match k:
    case 1:
        print('Monday','study day')
    case 2:
        print('Tuesday','study day')
    case 3:
        print('Wednesday','study day')
    case 4:
        print('Thursday','study day')
    case 5:
        print('Friday','study day')
    case 6:
        print('Saturday','Weekend')
    case 7:
        print('Sunday','Weekend')
    case _:
        print('invalid day')






#19
k = input('Drink code (T, C, J): ')
b = int(input('Quantity (1-10): '))
if 1 <= b <= 10:
    match k:
        case 'T':
            drink = 'Tea'
            total = 2 * b
            status = "Large order" if total >= 20 else "Regular order"
            print(drink, b, total, status)
        case 'C':
            drink = 'Coffee'
            total = 4 * b
            status = "Large order" if total >= 20 else "Regular order"
            print(drink, b, total, status)
        case 'J':
            drink = 'Juice'
            total = 3 * b
            status = "Large order" if total >= 20 else "Regular order"
            print(drink, b, total, status)
        case _:
            print('Wrong drink code')
else:
    print('Wrong quantity')




#20
ID=input('write your student code:')
c=len(ID)
if c==8:
    if ID.isascii() and ID.isdecimal():
        print('Student ID accepted')
    else:
        print('Invalid ID: Must contain only ASCII digits (0-9).')
else:
    print('Invalid ID: Must be exactly 8 characters long.')








#21
y_PIN=input('Write your PİN')
PIN="0427"
if len(y_PIN)==0:
    print('PIN is required')
elif len(y_PIN)!=4:
    print('PIN must have 4 digits')
elif not(y_PIN.isascii() and y_PIN.isdecimal()):
    print('Digits only')
elif y_PIN==PIN:
    print("Access granted")
else:
    print('Incorrect PIN')
    







#22
pn=input()
k=0
c=0
p=3

if len(pn)==0 or len(pn)!=10:
    print('phone number must have 10 ASCII digits')
    c=1
elif pn[0]!='0':
    print('phone number must begin with 0')
    c=1
elif not(pn.isdecimal() and pn.isascii()):
    print('phone number must contain only ASCII digits')
    c=1
elif k==0:
    t=pn[0:3]
    match t:
        case '050':
            p=1
        case '051':
            p=1
        case '055':
            p=1
        case '070':
            p=1
        case '077':
            p=1
        case '099':
            p=1
        case _:
            p=0
if p==0 and c!=1:
    print('your phone number can begin only with 050, 051, 055, 070, 077 or 099')
elif c!=1:
    print('phone number accepted') 







#23
balance=1000
PIN = "0427"
a=0
y_PIN=input('Write your PİN')
amount=input('write your amount')
if len(y_PIN)==0:
    print('PİN is required')
elif len(y_PIN)!=4:
    print('PIN must have 4 digits')
elif not(y_PIN.isascii() and y_PIN.isdecimal()):
    print('Digits only')
elif y_PIN==PIN:
    a=1
else:
    print('Incorrect PIN')


if a==1:
    if amount.isascii() and amount.isdecimal():
        amount=int(amount)
        if 10<=amount<=500:
            if amount%10==0:
                fee= 0 if amount<200 else 2
                if amount+fee<=balance:
                    print(amount,fee,balance-(amount+fee))
                else:
                    print('your amount exceed the balance')
            else:
                print('The amount must divisible by 10')
        else:
            print(' The amount must be between 10 and 500 AZN')
    else:
        print('The amount must contain only ASCII digits')








#24
product_code=input('write your product (K,M,H)')
quantity=input('write quantity of your product')
kupon_code=input('write your kupon kode (NONE or SAVE10)')
delivery_code=input('write your delivery code (P,S)')
a=0
c=4
p=0
k=0
match product_code:
    case 'K':
        code='Keyboard'
        cost=40
        a=1
    case 'M':
        code='Mouse'
        cost=20
        a=1
    case 'H':
        code='Headphones'
        cost=60
        a=1
    case _:
        print('product code must be only K,M or H')
if a==1:
    if quantity.isascii() and quantity.isdecimal():
        if '1'<=quantity<='5':
            quantity=int(quantity)
            subtotal=quantity*cost
            c=5
        else:
            print('The quatity must be between 1 and 5 ')
            
    else:
        print('The quantity must contain only ASCII digits')
        
    

if c==5:
    match kupon_code:
        case 'SAVE10':
            if subtotal>=100:
                discount=subtotal * 0.1
                total=subtotal-(subtotal*0.1)
            else:
                discount=0
                total=subtotal
            p=1
        case 'NONE':
            discount=0
            p=1
            total=subtotal
        case _:
            print('the kupon kode can be only NONE or SAVE10')
            

if p==1:
    match delivery_code:
        case 'P':
            delivery_cost= 0
            k=5
            total=total+delivery_cost
        case 'S':
            delivery_cost= 0 if total>=80 else 5
            k=5
            total=total+delivery_cost
        case _:
            print('the delivery kode can be only P or S')
            

if k==5:
    print(code,quantity,subtotal,discount,delivery_cost,total)








#25
ID=input('write your student code:')
age=input()
workshop_code=input('Write your workshop code(PY,WEB,CY)')
payment_amount=input('Write your payment amount')
k=0
t=0
a=0
p=0
z=0

c=len(ID)
if c==8:
    if ID.isascii() and ID.isdecimal():
        k=1
    else:
        print('Invalid ID: Must contain only ASCII digits (0-9).')
else:
    print('Invalid ID: Must be exactly 8 characters long.')


if k==1:
    if len(age)!=0:
        if age.isascii() and age.isdecimal():
            age=int(age)
            if 16<=age<=65:
                t=1
            else:
                print('The entered age does not meet the requirements.')
        else:
            print('Wrong age')
    else:
         print('Wrong age')


if t==1:
    match workshop_code:
        case 'PY':
            if age>=16:
                workshop='Python Basics'
                cost=30
                a=1
        case 'WEB':
            if age>=16:
                workshop= 'Web Development'
                cost=40
                a=1
        case 'CY':
            if age>=18:
                workshop= 'Cybersecurity'
                cost=50
                a=1
            else:
                print('Age requirement not met.')
        case _:
            print('The workshopcode can be only PY,WEB or CY')

if a==1:
    discount= cost*0.2 if 16<=age<=18 else 0
    total=cost-discount
    p=1

if p==1:
    if len(payment_amount)!=0:
        if payment_amount.isascii() and payment_amount.isdecimal():
            payment_amount=int(payment_amount)
            z=1
        else:
            print('your payment amount is wrong')
    else:
        print('your payment amount is wrong')

if z==1:
    if payment_amount<total:

        print('Insufficient payment',total-payment_amount )
    else:
        print('Registration confirmed',ID,workshop,discount,total, payment_amount-total) b










