# Trains

RECURSOS 
# /admin/{token} POST 
Se pasa el token en la url (el token no se genera en el proyecto, se genera previamente. El proyecto solo comprueba si ha sido firmado con su firma) y el 
-->REQUEST
```
{
  "origin":"Cieza",
  "destination":"Madrid",
  "price":200,
  "hour":"12:00"
}
```
<--RESPONSE
Devuelve el listado de trenes en JSON

# /admin/{token} GET 
No se pasa ningún parámetro en el REQUEST

<--RESPONSE
Devuelve el listado de trenes en JSON

