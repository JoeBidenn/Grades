# Grades
This is a prank for the school grading system


import time 
import sys
import progressbar

print("="*53, "LCSD GRADES", "="*54)

grades = input("username: ")
time.sleep(1)
if grades == "maiko":
 	print("")
else:
	print("unsuccessful!")
	exit(0)

grades = input("password: ")
time.sleep(1)
if grades == "admin":
	print("")
else:
	print("unsuccessful!")
	exit(0)

name = input("name: ")

print("="*50, "CHECKING DATABASE", "="*51)
def custom_len(value):
    # These characters take up more space
   

    total = 0
    for c in value:
        total += characters.get(c, 1)

    return total


bar = progressbar.ProgressBar(
    widgets=[
        ' ',
        progressbar.Bar(),
        ' ',
        progressbar.Counter(format='%(value)02d/%(max_value)d'),
    ],
    len_func=custom_len,
)
for i in bar(range(10)):
    time.sleep(.5)

print(name + " found!")
time.sleep(2)
print("")

grades = input("change " +  name + "'s" + " grades (y/n): ")
time.sleep(1)
if grades == "y":
	print("")
else:
	exit(0)

input("what percentage?: ")

print("="*52, "CHANGING GRADES", "="*51)
def custom_len(value):
    # These characters take up more space
   

    total = 0
    for c in value:
        total += characters.get(c, 1)

    return total


bar = progressbar.ProgressBar(
    widgets=[
        ' ',
        progressbar.Bar(),
        ' ',
        progressbar.Counter(format='%(value)02d/%(max_value)d'),
    ],
    len_func=custom_len,
)
for i in bar(range(10)):
    time.sleep(3)
print("finished grading!")

time.sleep(1)

print("grades changed!")

time.sleep(7)
exit(0)
	

