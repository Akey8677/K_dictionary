#almacenador

diccionario = {
 "CRINGE" : "Algo raro",
 "LOL" : "Una respuesta a algo gracioso",
 "XD" : "Una respuesta a algo gracioso",
 "SHEESH" : "ligera desaprobación",
 "AGGRO" : "ponerse agresivo/enojado",
 "ROFL" : "una respuesta a una broma",
}

#sistema

print("hola!")

for i in range(5):
    word = input("escribe una palabra que no entiendas(en MAYUSCULAS) :")

    #Buscar la palabra solicitada por la variable word
    if word in diccionario.keys():
         print(diccionario[word])
    else:
        #no se encontro dicha palabra
          print("no se encontro :(" )
