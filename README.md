# Respuesta al examen.

En este repositorio se encuentra el codigo necesario para compilar un .jar y ser desplegado en lambda AWS, dicha lambda se comunica con el usuario por medio de un API Gateway con los siguientes datos:

Endpoint:  https://l67vrx25ud.execute-api.us-east-1.amazonaws.com/dev/isMutant
Request body: 
{
  "dna": [
    "TTTTTT", "CAGTGC", "TTATGT", "AGAAGG", "CCCCTA", "TCACTG"
  ]
}
Response body:
"true" en caso de ser mutante
"false" en caso de no ser mutante.

Los indices pueden variar en contenido pero las cadenas que lo componente deben ser de igual longitud.


