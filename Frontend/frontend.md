## Implantación del frontend y conexión con el backend:

    1. En el repositorio, debemos buscar, dentro del archivo "main" de javascript, dos líneas que empiecen por "http://localhost..." y debemos sustutuirlas
        con nuestro enlace de conexión al backend, en nuestro caso : "https://apartamentos4v-backend-env.eba-2wshdusj.us-east-1.elasticbeanstalk.com?apikey=1234"
    2. Debemos comprimir en un .zip nuestro directorio con los ficheros del frontend
    3. Crearemos un nuevo EBS (de tipo plataforma docker) y cargaremos nuestro .zip con el código del frontend