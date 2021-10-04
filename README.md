- 👋 Hi, I’m @AsnaShafeeqa
- 👀 I’m interested in coding!
- 🌱 I’m currently learning coding in givemefive.com.
- 💞️ I’m looking to collaborate on my first project.
- 

<!---
AsnaShafeeqa/AsnaShafeeqa is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.


#Asna's First Project for GiveMeFive
print("Dearest reader, It has come to this Author's notice that you, who could possibly be a budding young fantasizer like me, are in search of the right book to start off your journey with. And it is with infinite amiability and on my side and palpable interest on yours, that we travel through this virtual library, where I shall be your virtual guide to get you hooked up with the \"parfaite\" novella! Bon voyage!") 
print("Perhaps your disney princess song like reveling moment is right now. \"Your the one I've been waiting for all of my life!\" I bet you can hear Elsa's voice while reading that. But now the time has arrived for you to embark on this wonderful quest with me as your guide. To make this a whole less daunting and a lot more of a play on the heartstrings, I shall be asking you a few queries to customize the best matched book based on your preferences.")
print("Now let the games begin!

question_bank={"1":"You\'ve got an hour to spend in the bookstore/library, where do you start?", "A2": "What do you look for when choosing a book?"}

options_bank={"1":["1-Bounce around from section to section browsing whatever looks good.", "Bounce around from section to section browsing whatever looks good.", "An hour in the bookstore - in my dreams!", "Check out my favorite authors to see if there's anything new."], "A2":["A book by one of my favorite authors.", "The next book on my \'to read\' list.", "Something a bit different/unusual.", "I usually choose books that have been recommended to me by friends."]}
for i in question_bank.keys():
   print(i, question_bank[i])
   for a in options_bank.keys():
    if a==i:
     print(a, options_bank[a])
