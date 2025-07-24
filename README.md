# Quiz-Game-
Quiz Game
print('welcom to learn with esprit')

player = input('do you want to paly ?')

if player.lower() !="yes":
    quit()
print ('ok lets play') 
score = 0

question = input("how many days do we have in week ?")
if question.lower() == "seven":
    print('correct')
    score += 1
else:
    print('incorrect')    

question = input("what is the capital of india ?")
if question.lower() == "delhi":
    print('correct')
    score += 1
else:
    print('incorrect')    

question = input("what is the largest ocean in the world ?")
if question.lower() == "pacific ocean":
    print('correct')
    score += 1
else:
    print('incorrect')    

question = input("which animal is known as the king of the jungle ?")
if question.lower() == "lion":
    print('correct')
    score += 1
else:
    print('incorrect')    

question = input("what is H20 commonly known as?")
if question.lower() == "water":
    print('correct')
    score += 1
else:
    print('incorrect')    

print ("your sccore"+str(score))
