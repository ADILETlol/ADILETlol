from random import randrange 
number = randrange(512)+1

guess =-1
k=0
while guess != number:
    guess = int(input('Введите число '))
    k+=1
    if guess > number:
        print('Загаданное число меньше')
    elif guess < number:
        print('Загаданное число больше')
print(number)
print('Вы отгадали число! \Количество ваших попыток составило',k)
