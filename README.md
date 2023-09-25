# MarkdownPractica1(Prueba)
## About
#### Basandonos en una red neuronal usando como base cientos de caras del ser humano, esta app esta pensada que dependiendo del estado de ánimo que muestre tu cara a la app, te recomiende series, películas, tipos de comida, actividades...
* * *
## Dependencias
> pandas 2.1, 2.0, 2.3
> <br>
> Matplotlib
> <br>
> tensorflow
> <br>
> numpy
> <br>
> Scikit-Learn
* * *
## Funciones Implementadas
* [ ] Red Neuronal
* [ ] Selector de opciones
* [ ] Implementación de cuentas Netflix...
* [x] Plan de Marketing
* * *
## Formula de Red de búsqueda
Utilizaremos esta revolucionara fórmula para hallar el grado de emoción del usuario

$$
  x^l_i = \int(\sum_j w^l_{ij}x^{l-1}_j+b^l_i)
$$

<p align="center">
dando lugar a esta grafica
<br>
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS9c3cwVcO64S4t8X7-SVBMSUid7wKeYnVTew&usqp=CAU)">
</p>

###### (Es posible que la formula de muestra no se corresponda en la actualidad)
~~~
import matplotlib.pyplot as plt
fig, ax = plt.subplots()
ax.pie([5, 4, 3, 2, 1])
plt.show()
~~~



<p align="center">
  Como se puede observar podemoes en la grafica que nuestro modelo de red neuronal, no solo podemos ver que calcula nuestra emociones
<br>
  Si no que ademas calcula la felicidadd basandose en el porcentaje de obesidad!
</p>
<br>
<br>

Para más información, visite el link para aprender más sobre este fascinante proyecto [Link Fascinante](https://www.freecodecamp.org/news/neural-networks-for-dummies-a-quick-intro-to-this-fascinating-field-795b1705104a)

