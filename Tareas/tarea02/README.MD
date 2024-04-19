# Tarea 02


### Primer ejercicio

Para este caso se nos pedía realizar un conteo de números desde el -100 hasta el número 200. 

Definimos la "x" como nuestra variable y luego ocupamos lo aprendido en clases, que es "for" y "range", para hacer nuestro comando, tal que "Para (for) x en el rango (range) de -100 a __201__"

Imprime (Print) nuestra variable (x)

 **Importante**
 
 Se pone 201 porque se toma el -100 como nùmero 0, lo que nos dara los siguientes 200 números, por lo que colocamos el 201.

 Si ponemos colocamos el rango en 200, se imprimiran del -100 hasta el 199. 


### Segundo ejercicio

Tomando los mismos datos del ejercicio anterior, ahora se nos piden todos los números entre el rango de -100 y 200 (201) que se puedan divivir por 6 y tengan resto 0.

Para esto usamos una condicional a traves del Si (if) y colocamos el simbolo de porcentaje (%), el cual nos da inmediatamente lo que necesitamos.

Por lo que colocamos: Para (for) x en el rango (range) de -100 a 201.
__Si x es divisible por 6 y da un resto igual a cero__, imprime x.


### Tercer ejercicio

Para este ejercicio se nos pedía realizar un algoritmo que pudiera sumar dos números. Para esto, usamos el input para que ponga un texto que acompañe un espacio en el que se colocen ambas variables numéricas (num1, num2).

 __Si queremos que la respuesta sea en números enteros, colocamos Int antes del input, pero si quisiéramos que la respuesta se expresara en decimal podemos usar float.__

 Definimos nuestra variable "Resultado" como la suma de las dos variables (num1,num2).

 A su vez ponemos una serie de condicionales para todas las combinaciones de respuesta con las que contamos. 

 Ocupamos el Si (if) para ver si el "Resultado" es menor a 200, se imprima un mensaje que diga "Menor a 200".

 Como queremos ver una serie de combinaciones ponemos Elif, para despues hacer lo mismo que antes pero tomando en cuenta otra combinacion. Si el "Resultado" es mayor a 200 y (and) menor a 250, se imprimira un mensaje que diga "Mayor a 200".

 Si el "Resultado" es mayor a 250, se imprimira un mensaje que diga "Mayor a 250".


### Cuarto ejercicio

Para este ejercicio, se nos pide algo similar al caso anterior, con una variable numérica y otra de texto, con condicionales y que se den distintos tipos de respuestas.

Para esto, colocamos un int antes del input y colocamos una pregunta sobre la edad.

Para la segunda variable, colocamos solamente un input ya que es una respuesta de texto y establecemos la respuesta que queremos obtener, en este caso un Si o un No.

Y aquí una serie de condicionales que ocuparemos:

- Si es mayor de 18 y responde que Si le gusta la música urbana, se imprime un mensaje que dice que "Es mayor de edad y le gusta la música urbana".

- Si es mayor de 18 y responde que No le gusta la música urbana, se imprime un mensaje que dice que "Es mayor de edad y no le gusta la música urbana".

- Si es menor de 18 y responde que Si le gusta la música urbana, se imprime un mensaje que dice que "Es menor de edad y le gusta la música urbana".

- Si es menor de 18 y responde que No le gusta la música urbana, se imprime un mensaje que dice que "Es menor de edad y no le gusta la música urbana".

Para que todas las condiciones se cumplan, ocupamos Else, en donde colocamos que de no poner un Si o un No con mayúscula, la respuesta a la segunda pregunta no será válida y se tendrá que ingresar otra respuesta. 