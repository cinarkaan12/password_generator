# password_generator
phyton şifre üretici

import random

cumle = "+-/*!&$#?=@abcdefghijklnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ1234567890"

uzunluk = int(input('Şifre uzunluğunu giriniz ='))

sifre = ""

for i in range(uzunluk):
     sifre += random.choice(cumle)

print(sifre)
