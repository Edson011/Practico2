# Sistemas de control de versiones

## 1: Mercurial
Mercurial, es un sistema de control de versiones distribuido ideal para usuarios poco experimentados o perfiles poco técnicos.

### Ventajas
°  Intuitivo y sencillo de manejar, con una curva de aprendizaje mucho más corta.
°  Veloz, potente y ligero.
°  Manejo sólido de archivos de texto plano y, también, binarios.
### Desventajas
°  No funciona bien con extensiones.
°  Presenta menos funcionalidades que Git.
°  Solo soporta complementos programados en Python.

## 2: SVN
SVN, a diferencia de Git, se basa en una arquitectura cliente-servidor. Presenta algunas funcionalidades interesantes, como versiones de enlaces simbólicos, soporte para directorios vacíos y registros de operaciones de copiar, mover, borrar y renombrar.

### Ventajas
°  Fácil de configurar y administrar.
°  Muy buen soporte para Windows.
°  Integración excelente con los principales IDE y las herramientas ágiles.
### Desventajas
°  Generación de ramas más compleja.
°  Repositorios más pesados.
°  Sin información sobre la hora de modificación de los archivos.
°  Sin soporte para versiones firmadas.

## 3: Monotone
Monotone es una herramienta de control de versiones distribuida de código abierto que puede integrarse en multitud de sistemas operativos.

### Ventajas
°  Excelente funcionamiento de la ramificación.
°  Buena documentación oficial.
°  Requiere poco mantenimiento.
°  Sencillo, con una curva de aprendizaje corta.
### Desventajas
°  Problemas de rendimiento en algunas operaciones.
°  No permite hacer checkout ni commit detrás del proxy.

## 4: CVS
CVS se basa en una arquitectura cliente-servidor como la de SVN, lleva presente mucho tiempo en el mundo del desarrollo y es una opción excelente para los proyectos de código abierto.

### Ventajas
°  Muy buena comunidad para la resolución de dudas y búsqueda de soluciones.
°  Gran soporte multiplataforma.
°  Línea de comandos robusta y útil para el uso de scripts.
### Desventajas 
°  No soporta revisiones firmadas, como SVN.
°  Poco soporte para el control de código fuente distribuido.
°  No contempla checkouts ni commits atómicos.

## 5: Bazaar
Bazaar es una herramienta de control de versiones que se basa en un modelo de repositorio distribuido y cliente-servidor. Proporciona compatibilidad con sistemas operativos multiplataforma y está escrito en Python 2, Pyrex y C.

### Ventajas
°  El seguimiento de directorios se admite muy bien en Bazaar (esta característica no está en herramientas como Git, Mercurial)
°  Su sistema de complementos es bastante fácil de usar.
°  Alta eficiencia y velocidad de almacenamiento.
### Desventajas
°  No es compatible con el pago / clonación parcial.
°  No proporciona conservación de la marca de tiempo





