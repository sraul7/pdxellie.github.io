---
layout: post
---

#Fortuane Teller Program

#Day 2

print("Hello, please enter your name.")
x=input()
print("Nice to meet you",x,".","Please enter your birthday.")
print("Please enter a 2-digit month, such as 01 for January.")
y=int(input())
print("Please enter a 2-digit day, such as 01 for the first of the month.")
z=int(input())

print("Please enter the birthday of someone else.")
print("Please enter a 2-digit month, such as 01 for January.")
a=int(input())
print("Please enter a 2-digit day, such as 01 for the first of the month.")
b=int(input())

print("Please enter the name of the person whose birthday you just entered:")
c=input()
print("Please enter your height in inches.")
height=int(input())
print("Do you play sports? Please enter 1 for yes or 2 for no.")
sports=int(input())
print("Do you play video games? Please enter 1 for yes or 2 for no.")
videogames=int(input())
S=y-z+height/b

print("Your lucky number is",S)


if(sports==1 and videogames==1):
  print("You are a Leo that will aspire to great things, as long as you continue to play videogames and become number 1 in fortnite, however you should consider finding a girlfriend.")
else:
  print("You are a Leo that will not aspire to great things, since you don't care about sports or video games, you should consider buying a PS4 or Xbox.")
print("Thank you",x,"for using this program. Good bye now.")
