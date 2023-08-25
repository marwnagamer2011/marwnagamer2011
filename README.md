import phonenumbers
print("hello")
name = input("Enter your name: ")
age = input("please enter you age: ")
phone_number = input("please enter you number phone: ")
email = input("please enter your gimal: ")
phone_num = phonenumbers.parse(phone_number, None)

age = int(age)

if age > 99:
    print("Error")
else:
    print("ok")

anser = input("please enter number from all this " )

anser = int(anser)

if anser > 99:
    print('you need at least 2 charcter')
else:
    print("okay")

m = 67

if anser == m :
    print("you anser is good you will recev the money")
    print("in this number phone\t" + phone_number)
else:
    print("your anser is incorrect")
