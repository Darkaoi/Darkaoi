def scitani(x, y):
    return x + y

def odcitani(x, y):
    return x - y

def nasobeni(x, y):
    return x * y

def deleni(x, y):
    if y == 0:
        return "Nelze dělit nulou!"
    else:
        return x / y

print("Vyber operaci:")
print("1. Sčítání")
print("2. Odčítání")
print("3. Násobení")
print("4. Dělení")

volba = input("Zadej volbu (1/2/3/4): ")

cislo1 = float(input("Zadej první číslo: "))
cislo2 = float(input("Zadej druhé číslo: "))

if volba == '1':
    print("Výsledek:", scitani(cislo1, cislo2))
elif volba == '2':
    print("Výsledek:", odcitani(cislo1, cislo2))
elif volba == '3':
    print("Výsledek:", nasobeni(cislo1, cislo2))
elif volba == '4':
    print("Výsledek:", deleni(cislo1, cislo2))
else:
    print("Neplatná volba")
