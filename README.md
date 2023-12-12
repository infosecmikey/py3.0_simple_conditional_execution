# py3.0_simple_conditional_execution

Name = input('Who are you? ')
print('Welcome', Name)
name = input('How about your last name? ')
print('Thank you,', Name + ' '+ name)
Age = int(input('How old are you? '))
if Age >= 30:
    print('Ouf, well as long as you feel young, right', Name)
if Age <= 29:
    print('Rejoice, you are still young', Name)

print('Welp, that is all the questions I have for today. Take care!')

# Remember that variables like "Age," in the context of this statement would
# push a str of the user's input, so it must be converted to an int().
