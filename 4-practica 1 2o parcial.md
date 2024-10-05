#almacenar las materias de un curso en lista junto a sus calificaciones
materia1 = input("ingresa la primer materia: "), int(input("calificacion de la materia 1: "))
materia2 = input("ingresa la segunda materia: "), int(input("calificacion de la materia 2: "))
materia3 = input("ingresa la tercera materia: "), int(input("calificacion de la materia 3: "))
materia4 = input("ingresa la cuarta materia: "), int(input("calificacion de la materia 4: "))
materia5 = input("ingresa la quinta materia: "), int(input("calificacion de la materia 5: "))

thislist = [materia1, materia2, materia3, materia4, materia5]
print(" ")
print("materias del 1 curso", thislist) #apareceran las materias del primer curso

print(" ")
for materia in thislist:
   print("Estoy cursando", materia[0], "y has obtenido", materia[1]) #se mostraran las materias que se estan cursando y la calificacion que has obtenido

![image](https://github.com/user-attachments/assets/03b8bf72-5477-48ca-847d-73a35cb57b7f)
![image](https://github.com/user-attachments/assets/259bda13-0530-4f67-8acc-eada6b4e1812)

