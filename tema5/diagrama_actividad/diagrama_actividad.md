<style>
  h1{
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

  #ex{
    border: none;
  }
</style>

<h1>EXPLICACIÓN DIAGRAMA DE ACTIVIDAD</h1>

<hr>

<img id="ex" src="img/diagrama.png">

<p>El diagrama empieza con la compra de un producto. Dicha compra genera un pedido de forma automática.</p>

<p>Después de esto, se seleccionan el artículo a comprar y la cantidad que se quiere comprar, estos dos elementos de forma separada. Los dos elementos se fusionan para seguir con el diagrama.</p>

<p>Una vez seleccionados, se añade el artículo al pedido que se creó al comienzo. En este punto existen dos opciones:</p>

<li>No se ha terminado de añadir artículos, por lo que se vuelve al comienzo del diagrama para seleccionar de nuevo un artículo y su cantidad.</li>

<li>Se ha terminado de añadir artículos, por lo que pasa a confirmarse el pedido.</li>

<p>Mientras se confirma el pedido, se comprueba el socio que realiza el pedido.</p>

<p>Según se puede ver el este diagrama, es necesario estar registrado para poder realizar un pedido, por lo que después de comprobar el socio existen dos opciones de continuar:</p>

<li>Registrarse para ser socio si no se es uno ya.</li>

<li>Pasar directamente a comprobar los datos bancarios del socio, ya que ya está registrado.</li>

<p>Además, si se ha tenido que tomar la primera opción (la de registrarse), después de terminar el registro se pasa automáticamente a la comprobación de los datos bancarios.</p>

<p>De nuevo, nos encontramos con varias bifurcaciones:</p>

<li>Los datos bancarios son correctos, por lo que se pasa a realizar el pago del pedido. El vendedor prepara el pedido para almacén y el estado del pedido pasa a ser "pendiente". Termina el diagrama.</li>

<li>Los datos bancarios son incorrectos, por lo que se pide que se rellenen los datos bancarios de nuevo.</li>

<p>Por último, en esta segunda opción (los datos bancarios son incorrectos), existen otras dos posibilidades:</p>

<li>Se intenta la corrección de los datos bancarios para poder pasar a pagar el pedido una vez sean correctos.</li>

<li>Se cancela el pedido para no realizar ningún pago y no comprar ningún artículo finalmente. El estado del pedido pasa a ser "cancelado".</li>