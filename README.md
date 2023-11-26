# appdev
App Development CrossPlatform
La recherche binaire est un algorithme de recherche efficace qui peut être utilisé pour trouver rapidement l’emplacement d’un élément spécifique dans une liste ou un tableau. Voici un exemple de script Python qui implémente la recherche binaire:

Python
Code généré par l'IA. Examinez et utilisez soigneusement. Plus d'informations sur la FAQ.

def binary_search(arr, x):
    low = 0
    high = len(arr) - 1
    mid = 0
 
    while low <= high:
        mid = (high + low) // 2
 
        if arr[mid] < x:
            low = mid + 1
 
        elif arr[mid] > x:
            high = mid - 1
 
        else:
            return mid
 
    return -1
 
arr = [2, 3, 4, 10, 40]
x = 10
 
result = binary_search(arr, x)
 
if result != -1:
    print("L'élément est présent à l'index", str(result))
else:
    print("L'élément n'est pas présent dans le tableau")
