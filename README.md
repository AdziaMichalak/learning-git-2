print("lista zakupów".capitalize())
lista = {
    "piekarnia".capitalize(): ["chleb".capitalize(), "bułki".capitalize(), "pączek".capitalize()],
    "warzywniak".capitalize(): ["marchew".capitalize(), "seler".capitalize(), "rukola".capitalize()],
}

for sklep, rzeczy in lista.items():
    print("idę do %s i kupuję tam: %s".capitalize() % (sklep, rzeczy))
