# Assignment-01- 
[assinment_no_1.py](https://github.com/user-attachments/files/27568536/assinment_no_1.py)
 
## Topics: String Functions, Type Casting, Input, Operators, and If-Else (Nested)

### 1. Ek string variable banayein jisme aapka full name ho, aur usse poora CAPITAL letters mein print karein.
"""

# Write your code here
name = "umar Khan".upper()
print(name)

"""### 2. User se unka fav fruit poochiye aur uski length (kitne characters hain) print karein."""

# Write your code here
fruit = input("enter your fav fruit")
print(f'your fav fruit is :' ,fruit )
print(f'food  legnth is :', len(fruit))

"""### 3. Ek sentence likhiye 'Python is fun' aur 'fun' ko 'awesome' se replace karke print karein."""

# Write your code here
sentence = "python is fun"
print(sentence.replace("fun","awesome"))

"""### 4. Check karein ke string 'Hello World' mein 'World' kaunse index par start hota hai."""

# Write your code here
string = "Hello World"
print(string.index("World"))

"""### 5. User se unka email address lein aur usse hamesha small letters (lowercase) mein convert karke dikhayein."""

# Write your code here
email = input("enter your email")
print(email.lower())

"""### 6. Ek sentence '   Python Programming   ' banayein aur uske extra spaces (suru aur aakhir ke) remove karein."""

# Write your code here
sentence = "   Python Programming   "
sen1=sentence.replace(" ","")
print(sentence)
print(sen1)

"""### 7. Ek string 'Welcome to coding' mein count karein ke 'o' letter kitni baar aaya hai."""

# Write your code here
string = "Welcome to coding"
print(string.count("o"))

"""### 8. User se unki age input lein aur usse integer mein convert karke print karein."""

# Write your code here
age = input("enter your age")
print(int(age))

"""### 9. Ek float value '15.99' ko integer mein convert karein. Output kya aaya?"""

# Write your code here
a = 15.99
print(int(a))

"""### 10. Do numbers ko input lein, dono ko add karein, lekin dhayan rahe input hamesha string hota hai, isliye unhe cast karein."""

# Write your code here
a = input("enter first number")
b = input("enter second number")
a = int(a)
b = int(b)
print(a+b)

"""### 11. Ek integer 100 ko string mein convert karein aur check karein ke uska type ab 'str' hai ya nahi."""

# Write your code here
a= 100
a = str(a)
print(f'the type is' ,type(a))
print(a)

"""### 12. User se price lein (e.g., 99.5) aur usse integer mein badal kar dikhayein."""

# Write your code here
price = input("enter price")
price = float(price)
print(int(price))

"""### 13. Ek string '10' aur doosri string '20' ko add (concatenate) karne ki jagah math wala addition (30) karke dikhayein."""

# Write your code here
num ='10'
num2 = '20'
print(int(num)+int(num2))

"""### 14. Ek variable mein '50.5' save karein aur usse float mein cast karne ke baad 10 plus karein."""

# Write your code here
a = "50.5"
a = float(a)
print(a + 10)

"""### 15. User se uska naam aur shehar (city) ka naam poochiye aur ek sentence print karein: 'Hello [Name], welcome to [City]'."""

# Write your code here
name = input("enter your name")
city = input("enter your city")
print(f'hello {name} welcome to {city}')

"""### 16. User se do numbers lein aur unka product (multiply) print karein."""

# Write your code here
num_1 = int(input('Enter the first number'))
num_2 = int(input('Enter second number'))
print('the ANSWER IS :',num_1 * num_2)

"""4
44### 17. User se unka favorite color poochiye aur print karein: 'I also like [color]'.
"""

# Write your code here
fav = input("enter your fav color")
print(f'i also like {fav}')

"""### 18. Ek chota program banayein jo user se uska birth year le aur uska current age calculate karein."""

# Write your code here
birth_year = int(input("enter your birth year:"))
birth_month =input("enter your birth month:")
current_year = 2026
age = current_year - birth_year
print(f'your age is {age}')

"""### 19. User se ek word input lein aur usse 5 baar print karein (string multiplication use karke)."""

# Write your code here
word = input("enter a word")
print(word * 5)

"""### 20. User se unka mobile number lein (as string) aur unhe batayein ke unhone kya number type kiya hai."""

# Write your code here
mobile = input("enter your mobile number")
print(type(mobile))

"""### 21. Do variables lein a=10, b=3. Inka remainder (modulo) nikal kar dikhayein."""

# Write your code here
a = 10
b = 3
print(a %b)

"""### 22. Check karein ke 15, 10 se bada hai AUR 20 se chota hai (Logical AND operator)."""

# Write your code here
a = 15
b= 10
c =20
if a > b and a < c:
  print(True)
else :
  print(False)

"""### 23. User se ek number lein aur check karein ke wo 100 se bada hai ya nahi (Comparison operator)."""

# Write your code here
a = int(input("enter a number"))
if a > 100:
  print(True)
else :
  print(False)

"""### 24. 2 ki power 5 (2^5) calculate karke print karein."""

# Write your code here
a = 2
b = a**5
print(b)

"""### 25. Check karein ke kya 50, 100 ke barabar hai (Equal to operator)."""

# Write your code here
a =50
b=100
if a==b:
  print('Barabar hai')
else :
  print('brabar nhi hai bhai')

"""### 26. Do Boolean values (True, False) lein aur 'OR' operator ka result dikhayein."""

# Write your code here
a = True
b = False
c = False
print(a or b or c)

"""### 27. User se ek number lein aur check karein ke wo Positive hai ya Negative."""

a = int(input('ener any no'))
if a >0 :
  print('positive')
else :
  print('negative')

"""### 28. Check karein ke user ki age 18 se zyada hai ya nahi, agar hai toh print 'Eligible for Vote'."""

# Write your code here
age = int(input('enter your age'))
if age >= 18:
  print('eligible for vote')
else :
  print('not eligible for vote')

"""### 29. Ek number input lein aur check karein ke wo Even hai ya Odd."""

# Write your code here
a = int(input('enter a number'))
if a % 2 == 0:
  print('even')
else :
  print('odd')

"""### 30. User se do numbers lein aur batayein dono mein se bada (Greater) kaunsa hai."""

# Write your code here
num_1 = int(input('Enter the first number'))
num_2 = int(input('Enter second number'))
if num_1 > num_2:
  print(f'{num_1} is greater')
else :
  print(f'{num_2} is greater')

"""### 31. Ek student ke marks input lein. Agar marks 33 se zyada hain toh 'Pass', warna 'Fail'."""

# Write your code here
marks = float(input('enter your marks'))
if marks >= 33:
  print('pass')
else :
  print('fail')

"""### 32. Check karein ke user ne jo string input ki hai wo empty toh nahi hai."""

# Write your code here
a = input('enter a string')
if a != '':
  print('not empty')
else :
  print('empty')

"""### 33. User se ek password input lein. Agar password 'python123' hai toh 'Access Granted', warna 'Wrong Password'."""

# Write your code here
PASSWORD =input('ENTER YOUR PASSWORD :')
if PASSWORD == 'python123':
  print('Access Granted')
else :
  print('Wrong Password')

"""### 34. Check karein ke user ka input kiya hua number zero hai ya nahi."""

num = int(input("enter any no :"))
if num == 0:
  print('zero')
else :
  print('not zero')

"""### 35. Student Grading System: 90+ (A), 80-89 (B), 70-79 (C), below 70 (D)."""

# Write your code here
marks = float(input('enter your marks'))
if marks >= 90:
  print('A')
elif marks >= 80:
  print('B')
elif marks >= 70:
  print('C')
else :
  print('D')

"""### 36. User se temperature lein. Agar 30 se zyada hai toh 'Hot', 15-30 hai toh 'Warm', 15 se niche hai toh 'Cold'."""

# Write your code here
temp = float(input('enter temperature'))
if temp >= 30:
  print('Hot')
elif temp >= 15:
  print('Warm')
else :
  print('Cold')

"""### 37. Ek number check karein ke wo 3 se divisible hai, 5 se divisible hai, ya dono se (FizzBuzz logic)."""

num = int(input('enter any no'))

if num % 3 ==0 and num% 5==0:
    print('divide by both')
elif num % 3 == 0   :
    print(f'num is divide by',3)
elif num % 5 ==0:
    print('num is divided by ' ,  5)
else:
    print('kese sai bhe nhi ho rha hai')

"""### 38. User se ek character lein aur check karein ke wo Vowel (a, e, i, o, u) hai ya Consonant."""

# Write your code here
char = input('enter charchter')
if char in ['a','e','i','o','u']:
  print('vowel')
else :
  print('consonant')

"""### 39. Bill Calculator: Agar shopping 5000 se upar hai toh 20% discount, 2000-5000 par 10% discount, warna No discount."""

# Write your code here
bill = float(input("kitnai ki shopiing ki hai apnai"))
if bill >5000 :
  discount = bill *0.2
elif bill >= 2000:
  discount =  bill *0.1
else :
   discount = 0

final_amount = bill - discount

print(f"Original Amount{bill}:")
print(f"Discount: {discount}")
print(f"Final Amount to Pay: {final_amount}")

"""### 40. Ek person ki age check karein: 0-12 (Child), 13-19 (Teenager), 20-59 (Adult), 60+ (Senior Citizen)."""

# Write your code here
age = int(input("enter your age"))
if age <=12 :
  print('child')
elif age <=19:
  print('Teenager')
elif age <=59:
  print('Adult')
else :
  print('Senior Citizen')

"""### 41. Check karein ke ek saal (year) Leap Year hai ya nahi."""

# Write your code here
year = int(input("year dalo: "))

if year % 4 == 0:
    if year % 100 == 0:
        if year % 400 == 0:
            print("leap year hai")
        else:
            print("leap year nahi hai")
    else:
        print("leap year hai")
else:
    print("leap year nahi hai")

"""### 42. User se week number (1-7) lein aur corresponding day (Monday, Tuesday...) print karein."""

from os import error
# Write your code here
week_number = int(input("enter week number :"))
if week_number == 1:
  print('Today is Monday')
elif week_number == 2:
  print('Today is Tuesday')
elif week_number == 3:
  print('Today is Wednesday')
elif week_number == 4:
  print('Today is Thursday')
elif week_number == 5:
  print('Today is Friday')
elif week_number == 6:
  print('Today is saturday')
elif week_number == 7:
  print('Today is Sunday')
else:
   print('error')

"""### 43. Ek simple calculator banayein (+, -, *, /) symbols ke basis par operation perform karein."""

# Write your code here

"""* *### 44. User ka weight aur height le kar BMI category batayein (Underweight, Normal, Overweight)."""

weight = float(input("Apna weight (kg) enter karein: "))
height = float(input("Apni height (inches) enter karein: "))

bmi = weight / (height ** 2)

print("Aapka BMI hai:", round(bmi, 2))

if bmi < 18.5:
    print("Category: Underweight")
elif bmi < 25:
    print("Category: Normal")
else:
    print("Category: Overweight")

"""### 45. ATM Machine Logic: Pehle PIN check karein, agar sahi ho toh Amount poochiye, agar account balance se kam amount ho toh 'Withdrawal Success'."""

# Write your code here
pin = int(input("Enter your PIN: "))

if pin == 1234:
    amount = int(input("Enter withdrawal amount: "))
    balance = 50000

    if amount <= balance:
        print("Withdrawal Success")
    else:
        print("Insufficient Balance")

else:
    print("Incorrect PIN")

"""### 46. Login System: Pehle Username check karein, agar match ho tabhi Password check karein."""

# Write your code here
username = input("Enter username: ")

if username == "admin":
    password = input("Enter password: ")

    if password == "1234":
        print("Login Successful")
    else:
        print("Incorrect Password")

else:
    print("Username not found")

"""### 47. Largest of Three: User se 3 numbers lein aur nested if-else use karke sabse bada number dhoondein."""

# Write your code here
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))
c = int(input("Enter third number: "))

if a > b:
    if a > c:
        print(a, "is biggest")
    else:
        print(c, "is biggest")
else:
    if b > c:
        print(b, "is biggest")
    else:
        print(c, "is biggest")

"""### 48. Ticket Booking: Pehle age check karein. Agar 18+ hai toh check karein 'Do you have ID?'. Agar ID hai toh 'Ticket Issued'."""

a = int(input("Enter your age: "))

if a >= 18:
    b = input("Do you have your ID? ")

    print(f"Your age is {a}")

    if b == "yes":
        print("Your Ticket is issued")
    else:
        print("Please provide your ID")

else:
    print("You are under age")

"""### 49. Admission System: Agar student ke marks 80+ hain, toh check karein unka interview clear hai ya nahi. Dono clear hone par 'Admission Done'."""

# Write your code here
marks = int(input("Enter your marks: "))

if marks >= 80:
    interview = input("Is interview clear? ")

    if interview == "yes":
        print("Admission Done")
    else:
        print("Interview not cleared")

else:
    print("Marks are less than 80")

"""### 50. Number Range: Check karein number positive hai ya nahi. Agar positive hai, toh check karein wo 100 se bada hai ya chota."""

# Write your code here
a = int(input("enter any no"))
if a  >= 0 :
  print ("No is postive")
  if a > 100:
    print("No is greater than 100")
  else :
    print("No is smaller than 100")
else :
  print("Given no is Negative")

"""### 51. Restaurant Order: Pehle Veg ya Non-Veg poochein. Veg mein Paneer ya Dal, Non-Veg mein Chicken ya Mutton ka option dein."""

# Write your code here
print("Veg ya Non-Veg?")
choice = input()

if choice == "Veg":
    print("Paneer ya Dal?")
    food = input()

    if food == "Paneer":
        print("Paneer order ho gaya")
    else:
        print("Dal order ho gayi")

else:
    print("Chicken ya Mutton?")
    food = input()

    if food == "Chicken":
        print("Chicken order ho gaya")
    else:
        print("Mutton order ho gaya")

"""### 52. Ek number input lein aur check karein ke wo Single digit hai, Double digit ya Triple digit."""

# Write your code here
num = int(input("Enter number: "))

if num < 10:
    print("Single digit")
elif num < 100:
    print("Double digit")
elif num < 1000:
    print("Triple digit")
else:
    print("More than 3 digits")

"""### 53. User se salary aur service years lein. Agar service 5 saal se zyada hai toh 5% bonus calculate karke final salary batayein."""

# Write your code here
salary = float(input("Enter your salary: "))
years = int(input("Enter service years: "))

if years > 5:
    bonus = salary * 0.05
    final_salary = salary + bonus
    print("Bonus:", bonus)
    print("Final Salary:", final_salary)
else:
    print("No bonus. Final Salary:", salary)

"""### 54. Ek triangle ki teen sides input lein aur batayein ke wo Equilateral, Isosceles ya Scalene hai."""

# Write your code here
a = int(input("Enter side 1: "))
b = int(input("Enter side 2: "))
c = int(input("Enter side 3: "))

if a == b and b == c:
    print("Equilateral Triangle")
elif a == b or b == c or a == c:
    print("Isosceles Triangle")
else:
    print("Scalene Triangle")

"""### 55. Month name check karke batayein ke us month mein kitne days hote hain (Jan, Feb...)."""

# Write your code here
month = input("Enter month name (Jan, Feb, Mar...): ")

if month == "Jan" or month == "Mar" or month == "May" or month == "Jul" or month == "Aug" or month == "Oct" or month == "Dec":
    print("31 days")

elif month == "Apr" or month == "Jun" or month == "Sep" or month == "Nov":
    print("30 days")

elif month == "Feb":
    print("28 or 29 days (Leap year case)")

else:
    print("Invalid month name")

"""### 56. Nested If-Else se check karein ke ek number Even hai aur 50 se bada

---

hai, ya Even hai aur 50 se chota hai.
"""

# Write your code here
num = int(input("Enter a number: "))

if num % 2 == 0:
    if num > 50:
        print("Number is Even and Greater than 50")
    else:
        print("Number is Even and Less than 50")
else:
    print("Number is Odd")

"""### 57. Student Result: Maths aur Science dono mein 40+ hone chahiye pass hone ke liye. Agar ek mein kam hain toh batayein kaunsa subject weak hai."""

# Write your code here
math = float(input('enter your marks in maths'))
science = float(input('enter your marks in science'))

"""### 58. Electricity Bill: Pehle 100 units free, next 100 units Rs 5/unit, uske baad Rs 10/unit."""

bill = int(input('enter you bill unit'))
if bill <= 100:
    print('free hai')
elif bill > 100:
    bill *5
    print(f'your bill is {bill}')
elif bill >=200:
    bill * 10
    print(f'Your bill is{bill}')
else :
    print('sahi unit dalo')

"""### 59. Game Level: Score 0-50 (Beginner), 51-100 (Intermediate). Agar Intermediate hai toh check karein user ne boss level par kiya hai ya nahi."""

# Write your code here
score = int(input("Enter your score: "))

if score >= 0 and score <= 50:
    print("Beginner Level")

else:
    if score >= 51 and score <= 100:
        print("Intermediate Level")

        boss = input("Did you pass boss level? ")

        if boss == "yes":
            print("Boss Level Cleared")
        else:
            print("Boss Level Not Cleared")

"""### 60. Final Challenge: Ek mini-project logic banayein jisme user se Username, Password, aur ek Security Question poochein nested loops aur if-else ke saath."""

# Write your code here
username = input("Enter username: ")

if username == "umar":

    password = input("Enter password: ")

    if password == "1234":

        question = input("What is your favourite color? ")

        if question == "black":
            print("Login Successful")

        else:
            print("Wrong Security Answer")

    else:
        print("Wrong Password")

else:
    print("Wrong Username")

