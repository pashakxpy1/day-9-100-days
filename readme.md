# Lesson 9

Знаки порівняння  при  операціях з числами

```py
# equal
5 == 5

# not equal
3 != 5

# greater than
5 > 3

# greater than or equal to
5 >= 3

# less than
3 < 5

# less than or equal to
3 <= 5
```

- This is because the way input works behind the scenes is it always assumes what you are typing is text (or a string) and gets stored as a variable in "". Casting is where we explicitly tell the computer that what we are typing is a number and not a letter.
```py
#--------------------
myScore = int(input("Your score: "))
#--------------------
if myScore > 100000:
  print("Winner!")
else:
  print("Try again 😭")

```

```py
#--------------
myPi = float(input("What is Pi to 3dp? "))
#--------------
if myPi == 3.142 :
  print("Exactly!")
else:
  print("Try again 😭")
```