import random

karakterler= "+-/*!&$#?=@abcdefghijklnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ1234567890"
a= int(input("Şifreniz kaç karakter?"))
b=""
if(a<8):
    print("Şifreniz çok kısa.")
    exit()
else:
    for i in range(a):
        b += random.choice(karakterler)
        print("Şifreniz: ",b)
