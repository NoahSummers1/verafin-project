def DC_Quiz():
    score = 0
    question1 = input("When Was the DC Universe created?")
    if question1 == ("1934"):
        print("correct")
        score += 1
    else:
        print("You're trash kid")
    question2 = input("What does 'DC' stand for?")
    if question2 == ("detective comics"):
        print("correct")
        score += 1
    else:
        print("Man you're not good at this, huh?")
    question3 = input("Which Superhero's weakness was made well known in the comics?")
    if question3 == ("superman"):
        print("correct")
        score += 1
    else:
        print("bruhhhhh")
    question4 = input("Which hospital did Harley Quinn work at as a psychologist?")
    if question4 == ("arkham asylum"):
        print("correct")
        score += 1
    else:
        print("yikes")
    question5 = input("Catwoman, Harley Quinn and Poison Ivy are members of What evil team?")
    if question5 == ("gotham sirens"):
        print("you knew that one? good job")
        score += 1
    else:
        print("don't sweat it no one would've got that one")
    question6 = input("What is Task Force X also called?")
    if question6 == ("suicide squad"):
        print("bloody right mate")
        score += 1
    else:
        print("come on that was easy")
    question7 = input("Who killed Thomas & Martha Wayne?")
    if question7 == ("joe chill"):
        print("correct. and in 'cold' blood too")
        score += 1
    else:
        print("Wrong. cold hearted man he was")
    question8 = input("What's the name of supermans father?")
    if question8 == ("jor-el"):
        print("out of this world!")
        score += 1
    else:
        print("maybe touch up on your extra terrestrial heritage")
    question9 = input("Which DC character did Stan Lee say was his favorite?")
    if question9 == ("Lobo"):
        print("got that one right")
        score += 1
    else:
        print("you're wrong....... get good scrub")
    question10 = input("Who was the founder of DC comics?")
    if question10 == ("Malcolm Wheeler-Nicholson"):
        print("correct")
        score += 1
    else:
        print("guess who's wrong again? YOU")
    question11 = input("What is Batmans favorite food?")
    if question11 == ("mulligatawny soup"):
        print("you're smart")
        score += 1
    else:
        print("that's the wrong answer bud")
    question12 = input("What animal did DC include in a lot of their comcis?")
    if question12 == ("ape"):
        print("monke say you right")
        score += 1
    else:
        print("monke say you wrong")
    question13 = input("What was Wonder Woman originally named?")
    if question13 == ("suprema"):
        print("the lasso of truth says you're right")
        score += 1
    else:
        print("i'm sorry to tell you but, you're wrong")
    question14 = input("What marvel writer worked for DC comics")
    if question14 == ("Stan Lee"):
        print("exelsior")
        score += 1
    else:
        print("well the 60's were fun but now we're paying for it. you're wrong btw")
    question15 = input("How much money did DC buy the rights to superman for?")
    if question15 == ("one hundred and thirty dollars"):
        print("correct")
        score += 1
    else:
        print("incorrect")
    question16 = input("Who now owns DC?")
    if question16 == ("warner bros"):
        print("correct")
        score += 1
    else:
        print("incorrect")
    question17 = input("Who Was the first DC superhero?")
    if question17 == ("superman"):
        print("correct")
        score += 1
    else:
        print("incorrect")
    question18 = input("Who kills the DC universe?")
    if question18 == ("lobo"):
        print("correct")
        score += 1
    else:
        print("incorrect")
    question19 = input("Whats the one sea animal that aquaman cant directly control?")
    if question19 == ("dolphins"):
        print("correct")
        score += 1
    else:
        print("incorrect")
    question20 = input("Who did superman box in a celebrity comic?")
    if question20 == ("muhammad ali"):
        print("correct")
        score += 1
    else:
        print("incorrect")
    EndScore = score * 5
    print(f"You got {score}/20 and got a {EndScore}% in the DC catagory")

game = input("Do you want to play Trivia Time?")
if game == ("no"):
        print("Have a nice day")
elif game == ("yes"):
    print("Time to play Trivia Time")
choice = input('select your category').lower()
if choice == "dc":
    DC_Quiz()

