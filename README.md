# sayitahminet

import random

sayi = random.randint(1,100)
hak = 10

while hak > 0:
  hak -=1
  tahmin = int(input("Tahmin Ediniz: "))

  if sayi == tahmin:
    print("Tebrikler Doğru Tahmin...")
    break

  elif sayi > tahmin:
    print("Yukarı")

  else:
    print("Aşağı")

  if hak == 0:
    print(f"Hakkınız Bitmiştir... Tutulan Sayı: {sayi} ")
