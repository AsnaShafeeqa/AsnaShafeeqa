- 👋 Hi, I’m @AsnaShafeeqa
- 👀 I’m interested in coding!
- 🌱 I’m currently learning coding in givemefive.com.
- 💞️ I’m looking to collaborate on my first project.
- 

<!---
AsnaShafeeqa/AsnaShafeeqa is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.

send it to hello@givemefive.ai

#Asna's First Project for GiveMeFive
print("Dearest reader, It has come to this Author's notice that you, who could possibly be a budding young fantasizer like me, are in search of the right book to start off your journey with. And it is with infinite amiability and on my side and palpable interest on yours, that we travel through this virtual library, where I shall be your virtual guide to get you hooked up with the \"parfaite\" novella! Bon voyage!") 
print("Perhaps your disney princess song like reveling moment is right now. \"Your the one I've been waiting for all of my life!\" I bet you can hear Elsa's voice while reading that. But now the time has arrived for you to embark on this wonderful quest with me as your guide. To make this a whole less daunting and a lot more of a play on the heartstrings, I shall be asking you a few queries to customize the best matched book based on your preferences.")
print("Now let the games begin!

question_bank={1:"You\'ve got an hour to spend in the bookstore/library, where do you start?", 2: "What do you look for when choosing a book?"}

options_bank={1:["1-Bounce around from section to section browsing whatever looks good.", "Bounce around from section to section browsing whatever looks good.", "An hour in the bookstore - in my dreams!", "Check out my favorite authors to see if there's anything new."], 2:["A book by one of my favorite authors.", "The next book on my \'to read\' list.", "Something a bit different/unusual.", "I usually choose books that have been recommended to me by friends."]}
for i in question_bank.keys():
   print(i, question_bank[i])
   for a in options_bank.keys():
    if a==i:
     print(a, options_bank[a])

#correct_option= make another dict if you want
score=0
count=1

#another method:
for key in question_bank:
 print(question_bank.get(key))
#or 
 print("Q", count, ")", question_bank_get(key))
 count+=1
 

#This is the kinda order taught in class:

#Asna's First Project for GiveMeFive
print("Dearest reader, It has come to this Author's notice that you, who could possibly be a budding young fantasizer like me, are in search of the right book to start off your journey with. And it is with infinite amiability and on my side and palpable interest on yours, that we travel through this virtual library, where I shall be your virtual guide to get you hooked up with the \"parfaite\" novella! Bon voyage!") 
print("Perhaps your disney princess song like reveling moment is right now. \"Your the one I've been waiting for all of my life!\" I bet you can hear Elsa's voice while reading that. But now the time has arrived for you to embark on this wonderful quest with me as your guide. To make this a whole less daunting and a lot more of a play on the heartstrings, I shall be asking you a few queries to customize the best matched book based on your preferences.")
print("Now let the games begin!")

question_bank={1:"You\'ve got an hour to spend in the bookstore/library, where do you start?", 2: "What do you look for when choosing a book?"}

options_bank={1:["A)Bounce around from section to section browsing whatever looks good.", "B)Bounce around from section to section browsing whatever looks good.", "C)An hour in the bookstore - in my dreams!", "D)Check out my favorite authors to see if there's anything new."], 2:["A)A book by one of my favorite authors.", "B)The next book on my \'to read\' list.", "C)Something a bit different/unusual.", "D)I usually choose books that have been recommended to me by friends."]}

correct_option={1:"a", 2:"b"}
score=0
count=1

#another method:
for key in question_bank:
 print(question_bank.get(key))
#or 
 print("Q", count, ")", question_bank.get(key))
 count+=1
 list_options=options_bank.get(key)
 for option in list_options:
   print(option)
 print("\n")#for 2 lines in between. #print("\r") also works to add one line in between.
 user_action=input("Chose the correct options : a, b, c or d.")
 if user_action.lower()==correct_option.get(key):
   print("Congratulations your answer is correct and you have got 10 points.")
   score+=10
 else:
    print("Sorry that was an incorrect answer.")
    #IF you want have a negative marking as well.
print("Your final score is", score)


![image](https://user-images.githubusercontent.com/86703952/135854925-eef9aee1-bed4-4de5-9474-f714bf750776.png)

# user login is a method to check whether the user has an ID in my website

users={"testuser1":"password1",
       "testuser2":"password2",       
       "testuser3":"password3"}
username=input("Username:") #Asna        #testuser1
password=input("Password:") #password1   #password1


getpassword=users.get(username, "User Not Found") #users.get(username)=value
print(getpassword)
#In the first case print shows user not found
#In the second case print shows password1

if getpassword==password:
  print("Login successful")
else:
  print("Login unsuccessful, pls Sign Up")

