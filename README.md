Justificación de la elección: GitHub Flow
Hemos seleccionado GitHub Flow como la estrategia de branching para nuestro proyecto de dos personas debido a los siguientes criterios clave:

Tamaño del equipo (2 personas):
Al ser un equipo muy reducido, modelos rígidos y complejos como GitFlow introducirían una sobrecarga administrativa innecesaria (gestión de múltiples ramas permanentes, fusiones en cadena y etiquetas complejas). GitHub Flow ofrece la simplicidad de una única rama principal (main), lo que permite una comunicación directa y fluida entre ambos desarrolladores sin fricciones burocráticas.

Frecuencia de despliegue esperada:
Nuestro objetivo es mantener una entrega continua y ágil, donde las nuevas funcionalidades o correcciones puedan pasar a producción de forma rápida y frecuente. GitHub Flow se alinea perfectamente con esta necesidad: cada cambio se aísla en una rama temporal de corta duración, pasa por una revisión rápida (Pull Request) y se integra de inmediato a main para ser desplegado, evitando los cuellos de botella de los ciclos de lanzamiento tradicionales.
