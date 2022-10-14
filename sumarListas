def SumaListas(Lista1, Lista2):
    resultadoCola = []
    suma = 0
    remanente = 0

    while (len(Lista1) != 0 and len(Lista2) != 0):

        suma = (remanente + Lista1[-1] + Lista2[-1])


        resultadoCola.append(suma % 10)


        remanente = suma // 10


        Lista1.pop(-1)
        Lista2.pop(-1)


    while (len(Lista1) != 0):
        suma = remanente + Lista1[-1]
        resultadoCola.append(suma % 10)
        remanente = suma // 10
        Lista1.pop(-1)


    while (len(Lista2) != 0):
        suma = remanente + Lista2[-1]
        resultadoCola.append(suma % 10)
        remanente = suma // 10
        Lista2.pop(-1)


    while (remanente > 0):
        resultadoCola.append(remanente)
        remanente //= 10


    resultadoCola = resultadoCola[::-1]

    return resultadoCola



def display(res):
    s = ""
    for i in res:
        s += str(i)

    print(s)

lista1 = [3, 4,5,6,7,8,  9]


lista2 = [ 5,7,8,9,4,5,69]
print(SumaListas(lista1,lista2))
