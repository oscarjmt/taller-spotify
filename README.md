# Analiza tu música de Spotify

Este taller esta dirigido para personas interesadas en estudiar data science.

La actividad consiste en extraer las canciones guardadas en las me gusta del usuario, para luego separalas en clusters. El objetivo es que los participantes vean el proceso de data science sin necesidad de saber programar, y que su tarea sea analizar los clústers en Power BI. Finalmente se deben asignar un nombre para cada clúster según las características que encuentren, con lo que se estaría creando una playlist por cada grupo en la cuenta del usuario.


Importante:
- Probablemente no se tengan instaladas las libreraias adecuadas de googletrans y spotipy, por lo que se debe ejecutar lo sigueinte como administrador:
    - pip install spotipy
    - pip install googletrans==3.1.0a0

- Debe ingresar a spotify developer y en el dashbord crear un app. Debe poner el Client ID y el Client secret en la segunda celda del notebook de python.

- Dentro de la configuracion de la app en spotify developer, se debe colocar en Redirect URIs lo siguiente: http://localhost:7777/callback

- Antes de que un usuario inicie sesión con el notebook de python, se debe haber regsitrado su correo previamente en la app de spotify developer.

- El usuario que ingresan en el notebook sirve unicamente para el cache, independiemiente de que nombre se ponga en el notebook se abrira una ventan nueva para inciar sesión con spotify. Si ya hay una cuenta iniciada en el navegador se toma esa cuenta de forma automática. Si se ingresa un nombre en el notebook con el cual ya se realizó un inicio de sesión, automaticamente con el cache se accede a la cuenta. Esto vence después de cierto tiempo, pero lo recomendable es eliminar el cache en cuento el usuario termine con el taller.

- A la hora de querer utilizar un usuario diferente debe cerrar sesion de spotify en su navegador, ya que de lo contrario se inicairá seisión automatiicamente con la cuenta que tenga sesión iniciada en ese navegador.

