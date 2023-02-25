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
</style>

<h1>ACTIVIDAD DÍA 20/02/2023</h1>

<hr>

<p><b>1. Modifica el siguiente caso de uso de la gestión de una cita del SAS:</b></p>

<img src="img/1.1.png">

<p>Respuesta:</p>

<img src="img/1.2.png">

<p><b>2. Explica el siguiente diagrama de secuencia. ¿Lo consideras válido? ¿Lo modificarías de alguna forma?</b></p>

<img src="img/2.1.png">

<p>Este diagrama representa el proceso que se realiza para que un paciente pueda pedir una cita médica.</p>

<p>Para empezar, el paciente realiza la solicitud, que se envía al sistema del centro médico. Comienza el proceso de validación del paciente: si el paciente es validado correctamente, se pasa a la siguiente fase; sino, se vuelve un paso atrás y el paciente deberá realizar la solicitud de nuevo (preferiblemente después de arreglar los problemas con su validación).</p>

<p>La siguiente fase es la validación del médico, seguida de la validación de la fecha y hora de la cita, las cuales siguen el mismo proceso que la verificación del paciente: comprobar que no hay ningún error con ninguna de las entidades o elementos para que la cita se pueda registrar sin ningún inconveniente.</p>

<p>Una vez se ha realizado la validación completa, la cita se añade/registra en el sistema y esta lista para ser realizada en la fecha y hora y con el médico y el paciente correspondiente.</p>

<p><b>3. Dibuja un diagrama de secuencia que nos explique el funcionamiento que tiene un usuario de un metro en cuanto a la venta de tickets de metro. Deberá existir un actor y dos objetos llamados "venta de tickets" y "tickets".</b></p>

