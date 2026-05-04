1. ¿Por qué es conveniente incluirlo?
 Es conveniente porque evita que archivos innecesarios o sensibles se suban a la nube. Sus beneficios principales son:
  Limpieza: Evita subir archivos temporales, ejecutables (como .exe), o carpetas de dependencias pesadas (como node_modules).
   Seguridad: Impide que subas por accidente contraseñas, llaves de API o configuraciones personales.
    Colaboración: Evita conflictos entre compañeros. Por ejemplo, no quieres subir los archivos de configuración de tu VS Code si tu compañero usa IntelliJ.
    
   2. ¿Cuándo se debe hacer?
    Lo ideal es crearlo al inicio del proyecto, justo después de hacer git init o apenas clonas el repositorio.

     3. ¿Cómo configurarlo?
      Es un archivo de texto plano sin nombre, solo con la extensión .gitignore. Se configura escribiendo un patrón por línea.


       Para ignorar un archivo "ignorado.txt", la regla consiste en escribir el nombre exacto del archivo en una línea nueva dentro del archivo .gitignore. La regla sería simplemente esta: ignorado.txt
        Explicación de la regla: Al escribir el nombre completo con su extensión, Git buscará cualquier archivo que coincida exactamente con ese texto en el directorio donde esté el .gitignore y dejará de rastrear cualquier cambio que le hagas.