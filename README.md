# verafin-project

from guizero import App

app=App(title="Triva Time")

app.display()


answer4 = input("Who killed Han Solo? ")
if answer4 == "kylo ren":
        print("CORRECT")
        TotalCorrect += 1
else: print("INCORRECT")


finalcorrect = TotalCorrect * 5
print (f"You got {TotalCorrect}/20 and got a {finalcorrect}% in the Star Wars category")


Score = 0
mvanswer15 = input("Who is wanda's brother(First Name)? ")
if mvanswer15 == "pietro":
        print("CORRECT")
        Score += 1
else: print("INCORRECT")
mvanswer16 = input("What is the gamer tag of the person thor was playing fortnite with? ")
if mvanswer16 == "noobmaster69":
        print("CORRECT")
        Score += 1
else: print("INCORRECT")
mvanswer17 = input("Who is the pink woman who lives in the bottom of peter quills ship(First Name)? ")
if mvanswer17 == "Bereet":
        print("CORRECT")
        Score += 1
else: print("INCORRECT")
mvanswer18 = input("ant man shrinks using what partial? ")
if mvanswer18 == "pym":
        print("CORRECT")
        Score += 1
else: print("INCORRECT")
mvanswer19 = input("Who was the person who killed the king of wakanda(First Name)? ")
if mvanswer19 == "zemo":
        print("CORRECT")
        Score += 1
else: print("INCORRECT")
mvanswer20 = input("Where does doctor strange go to cure his shaky hands? ")
if mvanswer20 == "kamar-taj":
        print("CORRECT")
        Score += 1
else: print("INCORRECT")

EndCorrect = Score * 5
print (f"You got {Score}/20 and got a {EndCorrect}% in the Marvel category")
