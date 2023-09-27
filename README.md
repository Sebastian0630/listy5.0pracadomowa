# listy5.0pracadomowa

# 1
moja_1_lista = []
while True:
    inp = (input('inp = '))
    if inp == 'stop':
        break
    if float(inp) <= 200 and float(inp) >= 1:
        moja_1_lista.append(float(inp))
print(moja_1_lista)

# 2

moja_2_lista = []
i = 0
while i < len(moja_2_lista):
    if moja_1_lista[i] % 2 == 0:
        if moja_1_lista[i] >= 50 and moja_1_lista[i] <= 70:
            moja_2_lista.append(moja_1_lista[i])
    i += 1
print(moja_2_lista)

# 3

moja_1_lista = []
while True:
    inp = (input('inp = '))
    if inp == 'stop':
        break
    elif int(inp) <= 6 and int(inp) >= 1:
        moja_1_lista.append(int(inp))
    else:
        print("podałeś złe liczby Nobie")

print(sum(moja_1_lista)/len(moja_1_lista))
        
# 4

inp = input('inp = ')
moja_lista = lista(inp)
i = 0
liczba_a = 0
while i < len(moja_lista):
    if moja_lista[1] == 'a':
        liczba_a += 1
    i += 1
print(moja_lista)
print('a =', liczba_a)
