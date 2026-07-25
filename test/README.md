# Casos de Prueba - Sistema Inclusivo

## Descripción

Esta carpeta contiene la documentación de los casos de prueba elaborados para el proyecto **Sistema Inclusivo**.

Los casos de prueba fueron desarrollados a partir de las historias de usuario definidas previamente, siguiendo un enfoque de pruebas funcionales para validar que las principales funcionalidades del sistema cumplan con los requerimientos establecidos.

Cada historia de usuario cuenta con dos casos de prueba:

- **Caso positivo:** valida el funcionamiento correcto del sistema utilizando datos válidos y siguiendo el flujo esperado.
- **Caso negativo:** valida la respuesta del sistema ante errores, datos inválidos o situaciones no permitidas.

---

# Objetivo de las pruebas

Los casos de prueba tienen como objetivo verificar:

- El correcto funcionamiento de las funcionalidades principales del sistema.
- La validación adecuada de datos ingresados por los usuarios.
- La respuesta del sistema ante diferentes escenarios.
- La accesibilidad y compatibilidad de la aplicación.
- La estabilidad y rendimiento durante el uso.

---

# Organización de los casos de prueba

La estructura de esta carpeta es la siguiente:

```text
test/
│
├── README.md
│
├── casos_historia_1.md
├── casos_historia_2.md
├── casos_historia_3.md
├── casos_historia_4.md
├── casos_historia_5.md
├── casos_historia_6.md
├── casos_historia_7.md
└── casos_historia_8.md
Relación entre historias de usuario y casos de prueba
Archivo	Historia de Usuario	Casos incluidos
casos_historia_1.md	Gestión de Actividades	Creación correcta y validación de campos obligatorios
casos_historia_2.md	Inscripción de Estudiantes	Inscripción exitosa y datos incompletos
casos_historia_3.md	Búsqueda por Cédula	Búsqueda existente y búsqueda sin resultados
casos_historia_4.md	Reportes en Excel	Generación de reporte y ausencia de información
casos_historia_5.md	Lectura de Contenido	Visualización correcta y contenido no disponible
casos_historia_6.md	Compatibilidad con Navegadores	Funcionamiento en navegadores soportados y problemas de compatibilidad
casos_historia_7.md	Rendimiento Óptimo	Respuesta rápida y comportamiento ante alta carga
casos_historia_8.md	Navegación por Teclado	Accesibilidad mediante teclado y validación de elementos no accesibles
Estructura de cada caso de prueba

Cada archivo contiene la siguiente información:

ID del caso de prueba.
Título del caso.
Objetivo de validación.
Precondiciones necesarias.
Datos de prueba utilizados.
Pasos de ejecución.
Resultado esperado.
Resultado obtenido.
Estado de ejecución.
Notas y evidencias.
Estado de ejecución

Actualmente los casos de prueba se encuentran en estado:

🟡 Pendiente

El resultado obtenido y las evidencias serán completados después de la ejecución de cada prueba.

Proyecto

Sistema Inclusivo

Documentación desarrollada siguiendo la metodología ágil Scrum y basada en las historias de usuario definidas durante el desarrollo del sistema.


En resumen:

📁 `test/README.md`  
⬇️  
Después de:

Organización de los casos de prueba

⬇️  
Antes de:

Estructura de cada caso de prueba

Ahí queda perfecto y el profesor al abrir la carpeta `test` verá primero la explicación y luego los archivos 
