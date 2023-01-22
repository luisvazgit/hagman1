# hagman1

Items a cumplir para este proyecto:
- Las palabras deben ser leidas desde un archivo de palabras en formato JSON (#1)
- Las palabras deben ser seleccionadas aleatoriamente para cada juego
- Una vez terminado un juego no se puede volver a seleccionar una palabra elegida en un juego anterior
- El numero de intentos para adivinar la palabra en cada juego puede ser leido via parametro de consola (#2), sino se especifica via consola entonces el programador debe seleccionarlo de manera arbitraria
- El nombre del archivo de palabras debe ser especificado via parametro de consola (#3)

#1: Formato: {data:[palabra1, palabra2, ..., palabra N]}. Ejemplo: https://www.randomlists.com/data/words.json
#2: python3 hagman.py -i 4 (tendras 4 intentos para adivinar una palabra)
#3: python3 hagman.py -f <nombre_archivo_palabras>

Ejemplo de invocacion:
- python3 hagman.py -i 4 -f mispalabras.json
- python3 hagman.py -f mispalabras.json (el numero de intentos no se especifico asi que se toma el definido por el programador)

¡Todos estos items deben cumplirse y ninguno es opcional!
