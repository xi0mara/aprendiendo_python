# Python 🐍 una herramienta, no un reptil
Python es una de las estrellas más brillantes en el firmamento de la programación, y el tiempo dedicado a aprenderlo es una muy buena inversión.
## ¿Qué es Python?
Python es un lenguaje de programación de alto nivel, interpretado, orientado a objetos y de uso generalizado con semántica dinámica. Es un lenguaje de programación utilizado para el desarrollo de aplicaciones web, software, ciencia de datos y machine learning. Es eficiente, fácil de aprender y se puede ejecutar en diferentes plataformas.
## ¿Por qué Python se llama Python? 
El nombre del lenguaje de programación Python proviene de una vieja serie de comedia de la BBC llamada Monty Python's Flying Circus, afición de su creador original *Guido Van Rossum*, por los humoristas británicos **Monty Python.** 
## ¿Quién creó Python?
Python fue creado por **Guido van Rossum**, nacido en 1956 en Haarlem, Países Bajos. Por supuesto, Guido van Rossum no desarrolló y evolucionó todos los componentes de Python.
La velocidad con la que Python se ha extendido por todo el mundo es el resultado del trabajo continuo de miles de (muy a menudo anónimos) programadores, evaluadores, usuarios (muchos de ellos no son especialistas en TI) y entusiastas.
Las circunstancias en las que se creó Python son un poco desconcertantes.
    <pre>
        <span class="pl-c"> Según Guido van Rossum:</span>
        <span class="pl-s1">"En diciembre de 1989, estaba buscando un proyecto de programación de "pasatiempo" que me mantendría ocupado </span>
        <span class="pl-s1">durante la semana de Navidad. Mi oficina(...) estaría cerrada, pero tenía una computadora en casa y no </span>
        <span class="pl-s1">mucho más en mis manos. Decidí escribir un intérprete para el nuevolenguaje de scripting en el que había estado </span>
        <span class="pl-s1">pensando últimamente: un descendiente de ABC que atraería a los hackers de Unix / C. Elegí  Python como un título</span>
        <span class="pl-s1">de trabajo para el proyecto, estando en un estado de ánimo ligeramente irreverente (y un gran fanático de </span>
        <span class="pl-s1">Monty Python's Flying Circus)."</span>
    </pre> 
## Los objetivos de Python
En 1999, Guido van Rossum definió sus objetivos para Python:
* Un **lenguaje fácil e intuitivo** tan poderoso como los de los principales competidores.
* De **código abierto**, para que cualquiera pueda contribuir a su desarrollo.
* El código que es tan **comprensible** como el inglés simple.
* Adecuado para tareas cotidianas, permitiendo tiempos de desarrollo cortos.

## Aplicaciones que usan Python
* Netflix
* Google
* Spotify
* Instagram
* Uber
* Dropbox
* Pinterest
* Instacart, otras.
## Operadores aritméticos 
En Python los operadores aritméticos son los que nos ayudan a hacer las distintas operaciones matemáticas.
- Suma (+) : 6+6 ⇒ 12
- Resta (-) : 6-6 ⇒ 0
- Multiplicación ( * ) : 6*6 ⇒ 36
- División (/) : 23/6 ⇒ 3.83
- División entera (//), Esto nos trae el **número entero** de la división : 21 // 5 ⇒ 4
- Modulo (%), Esto nos trae el **residuo** de la division : 21 % 5 ⇒ 1
- Potencia (**) : 2 ** 2 ⇒ 4
- Raiz : math.sqrt(9) también de esta manera 9 ** (0.5)
- Recordar que, **MATH** es una librería nativa de Python, la cual nos permite traer muchas funciones matemáticas como por ejemplo: raíz cuadrada,exponenciales, funciones trigonométricas, entre otras. Para llamarla debemos usar el keyword **import**

- 📑 **Python respeta las reglas matemáticas, es decir: 5 + 5 * 2 ⇒ 15**  (PEMDAS: parentesis, exponentes, multiplicación, división, adición y sustracción conforme aparezcan)

- 👀 **OPERADORES IN SITU**: Te permite escribir código como **"X = X + 3"** de manera más concisa como **"X += 3"** ( Lo mismo usando - , * , / y % )
    <pre>
        <span class="pl-c">## Ejemplo</span>
        
        <span class="pl-s1">x</span> <span class="pl-c1">=</span> <span class="pl-c1">4</span>
        <span class="pl-s1">x</span> <span class="pl-c1">*=</span> <span class="pl-c1">3</span>
        <span class="pl-en">print</span>(<span class="pl-s1">x</span>)
        <span class="pl-s1">12</span>
    </pre>

## ¿Qué es una variable?
Es una caja o lugar donde puedo guardar objetos: Números, textos, etc. Además, para asignar una variable debes usar siempre el signo **=**
- Identificador de mi varibale: Puedes usar guiones abajo, números y letras. Pero NO puedes comenzar con un número y debe estar siempre en minúsculas. 
    <pre>
        <span class="pl-c">## Ejemplo</span>
        
        <span class="pl-s1">user</span> <span class="pl-c1">=</span> <span class="pl-c1">"James"</span>
        <span class="pl-s1">y</span> <span class="pl-c1">=</span> <span class="pl-c1">3</span>
    </pre>

Si se desea nombrar una variable, se deben seguir las siguientes reglas:
- El nombre de la variable debe de estar compuesto por MAYUSCULAS, minúsculas, dígitos, y el carácter _ (guion bajo).
- El nombre de la variable debe comenzar con una letra.
- El carácter guion bajo es considerado una letra.
- Las mayúsculas y minúsculas se tratan de forma distinta (un poco diferente que en el mundo real - Alicia y ALICIA son el mismo nombre, pero en Python son dos nombres de variable distintos, subsecuentemente, son dos variables diferentes).
- El nombre de las variables no pueden ser igual a alguna de las palabras reservadas de Python. Ejemmplo: ['False', 'None', 'True', 'and', 'as', 'assert', 'break', 'class', 'continue', 'def', 'del', 'elif', 'else', 'except', 'finally', 'for', 'from', 'global', 'if', 'import', 'in', 'is', 'lambda', 'nonlocal', 'not', 'or', 'pass', 'raise', 'return', 'try', 'while', 'with', 'yield']

## ¿Cuáles son los componentes o elementos de una variable en Python?
*  Un nombre.
*  Un valor (el contenido del contenedor).
## ¿Cómo inicio Python desde la consola?
![image](https://user-images.githubusercontent.com/21746170/130538286-316869a2-ebec-4b5f-8aaf-eb4cded53561.png)
- En windows debes iniciar agregando : **py**
- En linux debes iniciar agregando: **python3**

Python necesita que sus **archivos tengan la extensión .py**. El uso de la extensión .py estándar permite que el sistema operativo abra estos archivos correctamente.

## Tipos de datos
![image](https://user-images.githubusercontent.com/21746170/130538900-bde691f3-a98a-4e2d-9734-7a2c1adcf587.png)

## Operadores lógicos
- **and** devuelve *Verdadero* si las todas las variables que estoy comparando son Verdaderas
- **or** devuelve *verdadero* si al menos una de las variables que estoy comparando es verdadera.
- **not**  para invertir el valor booleano.
## Operadores de comparación
- == Compara dos variables/valores, y devuelve *verdadero si son iguales* y falso si no lo son
- != Compara dos variables/valores, devuelve *verdadero si son diferentes* o falso de lo contrario
- *>* Compara dos variables/valores, devuelve *verdadero si el primero es mayor que* el segundo.
- < Compara dos variables/valores, devuelve *verdadero si el primero es menor que* el segundo.
- *>=*  Compara dos variables/valores, devuelve *verdadero si el primero es mayor o igual que* el segundo.
- <= Compara dos variables/valores, devuelve *verdadero si el primero es menor o igual que* el segundo.


 Desde Python 3 es posible usar el **&** como *and* y para utilizar el operador *or* se puede con el carácter **|** . Ejemplo: 
<pre>
   <span class="pl-s1">Trabaja & es_estudiante</span> 
   <span class="pl-en">Trabaja | es_estudiante</span>
</pre>


## Rivales de Python
Python tiene dos competidores directos, con propiedades y predisposiciones comparables. Estos son:
* Perl - un lenguaje de scripting originalmente escrito por Larry Wall.
* Ruby - un lenguaje de scripting originalmente escrito por Yukihiro Matsumoto.

## "HOLA PYTHON"
Una de las maneras más prácticas y sencillas de poder empezar en este mundo fascinante sin necesidad de tener la preocupación por la adquisición de un hardware de nivel es poder tener acceso a una cuenta gmail y aprovechar el servicio de Google Colab **https://colab.research.google.com/**
<pre>
    <span class="pl-s1">Google Colab (o Colaboratory) es una herramienta de Google que proporciona un entorno de Jupyter Notebook que no requiere configuración para su uso y se ejecuta completamente en la nube. Es un proyecto de investigación de uso gratuito lanzado por Google para fomentar la educación y la exploración en el área del aprendizaje automático.
    </span>
</pre>

![image](https://github.com/xi0mara/aprendiendo_python/assets/21746170/1fdf044a-d1b5-43fb-8ee7-28c554f49faf)


![image](https://github.com/xi0mara/aprendiendo_python/assets/21746170/5fff44fb-87ed-48d7-9c3d-814aa311670e)

Nos volveremos a ver ... en una nueva aventura.
