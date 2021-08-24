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
