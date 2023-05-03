<style>
  h1, h2, h3, h4, h5, h6{
    text-align: center;
    font-weight: bold;
    border: none;
    margin-bottom: 0px;
  }

  p{
    text-align: justify;
  }

  img{
    border: 2px solid black;
  }
</style>

<h1>CAJA BLANCA</h1>

<h4>CHRISTIAN MILLÁN SORIA</h4>

<h4>1º DAW TARDE</h4>

<hr>

<p><b>1. Si tenemos el siguiente algoritmo, que averigua si un número es primo o no:</b></p>

```
algoritmo primos
  escribir "Numero: "
  leer num

  cont<-2;
  swPrimo<-'V'

  mientras((cont<=(num/2))y(swPrimo == 'V'))hacer
    si((num mod cont)==0)entonces
      swPrimo<-F
    fin si

    cont<-cont+1
  fin mientras

  si(swPrimo=='V')entonces
    escribir num, " SI es primo"
  sino
    escribir num, " NO es primo"
  fin si
fin algoritmo
```

<p><b>Indica varios casos de prueba posibles, así como algún procedimiento de prueba.</b></p>

<p>Algunos casos de prueba posibles podrían ser, por ejemplo:</p>

<li>Caso de prueba válido: Ingresar el número 2, que es el número primo más pequeño.</li>

<li>Caso de prueba válido: Ingresar el número 7, que es un número primo.</li>

<li>Caso de prueba inválido: Ingresar el número 10, que no es un número primo.</li>

<li>Caso de prueba válido: Ingresar el número 23, que es un número primo.</li>

<li>Caso de prueba válido: Ingresar el número 29, que es un número primo.</li>

<p>Un posible procedimiento de prueba para verificar que el argoritmo funciona correctamente sería el siguiente (por pasos):</p>

<li>Paso 1: Ingresar un número primo como entrada, por ejemplo, 7.</li>

<li>Paso 2: Ejecutar el algoritmo.</li>

<li>Paso 3: Verificar que el algoritmo indique que el número ingresado es un número primo.</li>

<li>Paso 4: Repetir los pasos 1 a 3 con otros números primos para asegurarse de que el algoritmo los identifique correctamente.</li>

<li>Paso 5: Ingresar un número que no sea primo, por ejemplo, 10.</li>

<li>Paso 6: Ejecutar el algoritmo.</li>

<li>Paso 7: Verificar que el algoritmo indique que el número ingresado no es un número primo.</li>

<li>Paso 8: Repetir los pasos 5 a 7 con otros números que no sean primos para asegurarse de que el algoritmo los identifique correctamente.</li>

<li>Paso 9: Asegurarse de que el algoritmo no tenga errores de lógica para cualquier número de entrada mediante el análisis del código fuente y la verificación de los cálculos realizados en el código.</li>

<p><b>2. ¿Qué diferencia existe entre las pruebas de caja blanca y las de caja negra? En el ejemplo anterior, ¿en qué consistirían?</b></p>

<p>Las pruebas de caja blanca y las pruebas de caja negra son dos enfoques diferentes para realizar pruebas de software. La principal diferencia entre ambas radica en su enfoque de prueba.</p>

<p>Las pruebas de caja blanca se enfocan en la estructura interna del código fuente, es decir, su lógica, su diseño y su implementación. En este enfoque, el probador conoce el código fuente y puede examinar los datos de entrada y las rutas del programa para determinar si el comportamiento del software es correcto.</p>

<p>Por otro lado, las pruebas de caja negra se enfocan en el comportamiento externo del software, sin tener en cuenta cómo está diseñado o implementado el código. En este enfoque, el probador no conoce la estructura interna del código fuente y solo tiene acceso a la interfaz del software. El objetivo es probar las funcionalidades del software y sus resultados sin tener en cuenta el cómo se implementa.</p>