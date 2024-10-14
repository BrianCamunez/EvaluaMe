## EvaluaMe
# Escenario del proyecto

El profesor quiere una forma mas facil de poder valorar el trabajo de los alumnos, y que entre ellos tambien puedan valorar la de sus compañeros. Quiero que el ritmo de la clase
y la forma de puntar sea esa, a si que voy a hacer una aplicacion que haga lo antes nombrado

Para eso voy a necesitar primero los **casos de uso**

# Casos de uso general

La aplicación web debe permitir a un usuario registrarse con su nombre, apellidos, correo electrónico y contraseña, y posteriormente iniciar y cerrar sesión. Un usuario registrado podrá ver un listado de proyectos publicados por otros estudiantes, editar su perfil y subir una imagen de avatar.

Si el usuario registrado tiene el rol de **'estudiante'**, podrá:
Publicar sus propios proyectos con información como: título del proyecto, descripción, imágenes representativas, enlaces al código fuente o demos, estado del proyecto, etc.
Editar o eliminar sus proyectos publicados.
Realizar autoevaluaciones de sus proyectos basadas en criterios establecidos.
Evaluar los proyectos de sus compañeros mediante coevaluaciones, proporcionando comentarios y valoraciones.

El **profesor**, con el rol de **'administrador'**, podrá:
Gestionar los perfiles de todos los usuarios registrados en la plataforma (editar, borrar, asignar roles, etc.).
Revisar y moderar los comentarios y evaluaciones realizadas por los estudiantes.
Establecer los criterios y rúbricas de evaluación que se utilizarán en las autoevaluaciones y coevaluaciones.
Acceder a reportes y estadísticas sobre el desempeño de los estudiantes y la interacción en la plataforma.

# Fases de desarrollo

Para organizar el **desarrollo del proyecto** y cumplir con los objetivos establecidos, seguiremos las siguientes fases:

**Definición del proyecto y requisitos básicos**: Clarificar las expectativas de la aplicación y anotar cada funcionalidad considerando los diferentes roles de acceso.
**Definición de las versiones**: Dividir el trabajo en versiones operativas, cada una ampliando las funcionalidades de la anterior.
**Planificación del proyecto**: Utilizando la metodología Agile, dividir el proceso en historias y tareas para cada versión, asignar tiempos y representarlas mediante diagramas.
**Diseño de la interfaz**:
    Realizar un benchmarking para inspirarse en soluciones similares.
    Crear un modelo de usuarios.
    Diseñar prototipos de baja fidelidad (bocetos, wireframes).
    Desarrollar un mockup de alta fidelidad junto con una guía de estilos utilizando Figma.
    Realizar pruebas de usabilidad y ajustar los prototipos según los resultados.
**Programación del frontend (HTML/CSS/JS)**:
    Maquetar los prototipos en código.
    Implementar la lógica de validación en el lado del cliente.
**Programación del backend**:
    Utilizar un Backend como Servicio (BaaS) como SUPABASE para:
    Crear las bases de datos.
    Diseñar consultas SQL y funciones en PostgreSQL.
    Programar un ORM en JavaScript para el mapeo de la base de datos.
**Integración de frontend y backend**:
    Desarrollar la aplicación SPA (Single Page Application) a partir de los prototipos.
    Implementar la lógica de acceso a la base de datos utilizando el ORM.
    Programar el resto de funcionalidades (gestión de sesiones, control de roles, etc.).
**Análisis de usabilidad II**:
    Realizar pruebas de usabilidad adicionales y solucionar posibles conflictos detectados.
**Testing y despliegue en producción**:
    Diseñar un sistema de testing para crear pruebas unitarias.
    Configurar un entorno DevOps para trabajar con Integración Continua y Despliegue Continuo (CI/CD).
    Desplegar en producción cada una de las versiones.

# Versiones
El desarrollo del proyecto se dividirá en las siguientes versiones basadas en las funcionalidades a implementar:
**VERSIÓN 1.0**: Implementación de la publicación de proyectos y autoevaluaciones.
**VERSIÓN 2.0**: Implementación de las coevaluaciones entre estudiantes.
**VERSIÓN 3.0**: Implementación de un sistema avanzado de evaluación basado en rúbricas y criterios personalizados establecidos por el profesor.

