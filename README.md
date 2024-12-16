print("Welcome to Homes")
print("please enter your name")
name = input()
print("hello",name)
print("please enter your age")
age = input()
if int(age) >= 12:
  print("This is the story of a young man who lives in a city of war. You are that boy. Your goal is to get youself back home safely without being shot by the enemy. You will be given a series of choices that you will have to make. Good luck!")
else :
   print("you are not eligible for this game")

if int(age) >= 12:
  
  print("would you like to start the game?")
user_choice = input()
if user_choice == "yes" :
  print("You are done praying at a mosque. A shooting is starting to take place. The direction of where your house is situated, is where the gunshots are comming from. Your friends choose to hide in the mosque. Will you stick with your friends? or will you escape?")
print("1.yes")
print("2.No")
if(user_choice=="yes"):
  print("You and your friends will now need to find a safe place to hide. You       have a few 3 options.")
  print("1.The basement")
  print("2.The washroom")
  print("3.one of the hallways")

user_choice = input()
if user_choice == "The basement": 
  print("you have chosen the basement. You and your friends are now in the basement. You hear soldiers coming in. You now have two options. 1.You can hide in the closet. 2.You can escape through a small window, but the shooting is still ongoing.")
  if user_choice == "1":
    print("You have chosen the closet. A soldier has found you in there and has shot you dead.") 
  if user_choice == "2": 
    print( "You have escaped through the window. You are now running home as fast as you can, but you have been shot and killed.")

if user_choice == " The washroom" :
  print("You are now hiding in the washroom. Soldiers are now coming in. You have 2 options. 1. You can play dead. 2. You can try to sneak your way past the soldiers.")
  if user_choice =="1":
    print( "You have chosen to play dead. The soldiers thought that you were pre killed, and left you alone. You are now safe.")
    if user_choice =="2":
      print("You have chosen to sneak past the soldiers. The soldiers have found you and shot you dead.")  

if user_choice == "The hallway" :
  print("You hiding in a deep hallway. Soldiers are now coming in. You have 2 options. 1. You can play dead. 2. You can find a new place to hide.")
  if user_choice =="1":
    print("You have chosen to play dead. The soldiers thought that you were already killed and left you alone. You are now safe.")
    if user_choice == "2":
      print("You have been caught and killed.")

else: 
  print("You are now running away from the shooting. You have 2 options. 1. You can try to go home but the road is filled with soldiers. 2. You can go to a nearby store and try to hide there.")
  if user_choice == "1":
    print("You are trying to get home. The soldiers have layed a check post on the road. They have kidnapped you for not haveing your documents and shot you dead.")
    if user_choice == "2":
      print(" You are hiding in a nearby grocery store, where the soldiers have already visited. The soldiers did not find you and you are now safe.")




