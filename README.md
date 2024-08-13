# GIT
Git es un sistema de control de versiones distribuido que se ha convertido en el más utilizado en todo el mundo. Fue creado por Linus Torvalds, el famoso desarrollador del kernel de Linux, en 2005.

- Distribuido y flexible: A diferencia de sistemas anteriores como CVS o Subversion, en Git, cada copia de trabajo del código es también un repositorio completo. Esto permite trabajar de forma descentralizada y sin conexión.

- Git se adapta bien a una variedad de sistemas operativos y entornos de desarrollo integrados (IDE).

- Rendimiento sólido: Las operaciones básicas, como confirmar cambios, crear ramas y fusionar, están optimizadas para un rendimiento óptimo.

- Los algoritmos en Git aprovechan el conocimiento profundo sobre los patrones de acceso y modificaciones en los archivos de código fuente. Seguridad y confiabilidad.

# Historias de usuario
Las historias de usuario son breves requisitos o solicitudes escritas desde el punto de vista del usuario final. Se expresan en lenguaje común y se utilizan en metodologías de desarrollo ágil para especificar requisitos. Estas historias describen lo que un usuario quiere hacer con un producto de software.

Ejemplos de historias de usuario:

1.- Como Max, quiero invitar a mis amigos para que podamos disfrutar de este servicio juntos.

2.- Como Sascha, quiero organizar mi trabajo para sentir que tengo un mayor control.

3.- Como gestor, quiero poder comprender el progreso de mis compañeros para informar sobre nuestros éxitos y fallos.

# Patrones de arquitectura

Los patrones de arquitectura en software son soluciones reutilizables a problemas comunes en el diseño y estructura de sistemas de software. Proporcionan una forma de organizar y estructurar el código para abordar desafíos específicos de diseño, como escalabilidad, mantenimiento, y separación de preocupaciones.

1. Patrón de Arquitectura en Capas (Layered Architecture) Descripción: Divide el sistema en capas, donde cada capa tiene una responsabilidad específica y solo interactúa con las capas adyacentes. Comúnmente se ve en aplicaciones empresariales.

Ejemplo de Capas:

- Capa de Presentación: Maneja la interfaz de usuario. Capa de Aplicación: Contiene la lógica de negocio. Capa de Dominio: Define las entidades del negocio. Capa de Persistencia: Gestiona el acceso a datos. Ventajas:

- Separación de preocupaciones: Facilita la comprensión y el mantenimiento. Reusabilidad: Las capas pueden ser reutilizadas en diferentes contextos. Desventajas:

- Sobrecarga: Puede haber una sobrecarga por las múltiples capas. Rendimiento: Las interacciones entre capas pueden afectar el rendimiento.

2. Patrón MVC (Modelo-Vista-Controlador) Descripción: Divide la aplicación en tres componentes principales:

i. Modelo: Maneja los datos y la lógica de negocio.
ii. Vista: Presenta los datos al usuario.
iii. Controlador: Interactúa con el modelo y actualiza la vista. Ventajas:

- Separación de responsabilidades: Facilita la gestión y evolución de las distintas partes. Escalabilidad: Mejora la capacidad de manejar cambios en la interfaz y la lógica de negocio de manera independiente. Desventajas:

- Complejidad: Puede ser más complejo de implementar inicialmente.

3. Patrón Microservicios Descripción: Divide una aplicación en servicios pequeños e independientes, cada uno con una responsabilidad específica. Estos servicios se comunican entre sí a través de APIs.

Ventajas:

- Escalabilidad: Cada microservicio puede escalar de manera independiente. Despliegue independiente: Los cambios en un microservicio no afectan a los demás. Desventajas:

- Complejidad en la comunicación: La gestión de comunicación entre servicios puede ser complicada. Gestión de datos distribuida: Mantener la consistencia de datos puede ser desafiante.

