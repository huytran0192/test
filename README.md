import random
chu = "abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ"
so = "0123456789"
kytudacbiet = "!@#$%^&*"
matkhau = ""
for i in range (15):
    matkhau += random.choice(chu + so + kytudacbiet)
print ("mat khau cua ban la: ", matkhau)
