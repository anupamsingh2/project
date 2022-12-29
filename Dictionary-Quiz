from random import sample

Questions = ['Russia has a larger surface area than Pluto.','There are as many stars in space than there are grains of sand on every beach in the world.', 
                 'For every human on Earth there are 1.6 million ants.','On Jupiter and Saturn it rains diamonds.', 'Scotland’s national animal is the phoenix.', 
                  'A banana is a berry.', 
                  'An octopus has three hearts.', 
                  'There are 10 times more bacteria in your body than actual body cells.', 
                  'Rhode Island is the closest US state to Africa.', 
                  'Shakespeare made up the name “Sarah” for his play Merchant of Venice.',
             'Python is a case sensitive language','Python is a interpreted language','Python is a machine language','Python runs on the chrome browser',
'Python is developed by Guido van Rossum', 'Secondary storage, similar to main memory, also stores programs and data',"Each computer has its own machine language which is made of streams of 0's and 1's",
 'Symbolic languages use mnemonics to represent the various machine language instructions',
 'Only the machine and symbolic languages can be understood by computer hardware',
 'One benefit to the use of symbolic languages is improved programming efficiency compared to a machine language',
 'High level languages are portable to many different computers',
 'the process of converting a high-level language to machine language is known as compilations',
 'The software used to write programs is known as a text editor',
 'A source file contains code written in a programming language that is to be sent to the compiler',
 'One purpose of preprocessor commands is to tell the preprocessor to make substitutions in code',
             ]

Answers = ['True','False','True','True','False','True','True','True','False','True','True','True','False','False','True','True','True','True','True','True','True','True',
           'True','True','True']
name=input("enter your name:   ")
print("Hello",name,"welcome to the quiz world")
print("Answer the following questions in true and false format")
print("  _______ "+"let's start"+" _______")
print(" ")
num_right = 0
score1=0
key = list(zip(Questions, Answers))
s = sample(key, 5)
for i in s:
    print(i[0])
    user_answer = input('Your answer(true or false): ')
    if user_answer.lower() == i[1].lower():
        print('Correct!!!')
        num_right += 1
        score1+=1
    else:
        print('Not Correct')
print('{}/5 Questions Correct'.format(num_right))
print("             ")
print(" score: ",score1)


print(" ")
print(" ")
print("welcome to the second round")
print(" ") 
num_right = 0
score2=0
key = list(zip(Questions, Answers))
s = sample(key, 5)
for i in s:
    print(i[0])
    user_answer = input('Your answer: ')
    if user_answer.lower() == i[1].lower():
        print('Correct!!!')
        num_right += 1
        score2+=1
    else:
        print('Not Correct')
print('{}/5 Questions Correct'.format(num_right))
print("             ")
print("score: ",score2)


#3 round
print(" ")
print(" ")
print("welcome to the third round")
print(" ")
num_right = 0
score3=0
key = list(zip(Questions, Answers))
s = sample(key, 5)
for i in s:
    print(i[0])
    user_answer = input('Your answer: ')
    if user_answer.lower() == i[1].lower():
        print('Correct!!!')
        num_right += 1
        score3+=1
    else:
        print('Not Correct')
print('{}/5 Questions Correct'.format(num_right))
print("             ")
print("score: ",score3)



# 4 round
print(" ")
print(" ")
print("welcome to the fourth round")
print(" ")

num_right = 0
score4=0
key = list(zip(Questions, Answers))
s = sample(key, 5)
for i in s:
    print(i[0])
    user_answer = input('Your answer: ')
    if user_answer.lower() == i[1].lower():
        print('Correct!!!')
        num_right += 1
        score4+=1
    else:
        print('Not Correct')
print('{}/5 Questions Correct'.format(num_right))
print("             ")
print("score: ",score4)

# 5 round
print(" ")
print(" ")
print("welcome to the fifth round")
print(" " )
num_right = 0
score5=0
key = list(zip(Questions, Answers))
s = sample(key, 5)
for i in s:
    print(i[0])
    user_answer = input('Your answer: ')
    if user_answer.lower() == i[1].lower():
        print('Correct!!!')
        num_right += 1
        score5+=1
    else:
        print('Not Correct')
print('{}/5 Questions Correct'.format(num_right))
print("  ---------------------------------------------------------------------           ")
print("score: ",score5)
print(" " )
print(" ")
print("congratulations!!!!  you attempted all rounds ")

print("participant name: ",name)
print("final score: ",score1+score2+score3+score4+score5)
