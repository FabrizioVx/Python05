# Python05
Ordenamiento 
Def BubbleSort(lista) :
    For i in range(lista-1,0,-1):
        For j in range(i) :
             If lista[j] [1]>lista[j+1][1]:
                    aux = lista[j]
                     lista=lista[j+1]
                     lista[j+1]= aux
    return lista 
