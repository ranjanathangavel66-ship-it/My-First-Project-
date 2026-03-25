# Student Grade Calculator

name = input("Enter student name: ")

marks1 = int(input("Enter marks for Subject 1: "))
marks2 = int(input("Enter marks for Subject 2: "))
marks3 = int(input("Enter marks for Subject 3: "))

total = marks1 + marks2 + marks3
average = total / 3

print("\nStudent Name:", name)
print("Total Marks:", total)
print("Average:", average)

if average >= 90:
    print("Grade: A")
elif average >= 75:
    print("Grade: B")
elif average >= 50:
    print("Grade: C")
else:
    print("Grade: Fail")
    https://github.com/ranjanathangavel66-ship-it/Simple-program-
