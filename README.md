import random


password = "+-/*!&$#?=@abcdefghijklnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ1234567890"
pass_length = int(input('Введи длину пароля:'))
elements = ''

for i in range (pass_length):
    elements += random.choice(password)


print(elements)
