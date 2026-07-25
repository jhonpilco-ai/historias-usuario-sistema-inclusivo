# Casos de Prueba - Sistema Inclusivo

## Historia de Usuario 7: Rendimiento Óptimo

**Módulo:** Rendimiento del sistema  
**Rol involucrado:** Usuario  
**Tipo de prueba:** Prueba de rendimiento

Esta historia valida que el sistema pueda responder rápidamente, mantener estabilidad y permitir al usuario realizar sus actividades sin demoras.

---

# Caso de Prueba Positivo

## ID del caso de prueba

TC-013

## Título

Carga rápida del sistema durante el uso normal

## Objetivo

Validar que las páginas y funcionalidades principales del sistema respondan en tiempos adecuados durante una operación normal.

## Precondiciones

- El sistema debe encontrarse disponible.
- Debe existir conexión estable al servidor.
- El usuario debe contar con acceso al sistema.

## Datos de prueba

| Campo | Valor |
|---|---|
| Usuario | Usuario registrado |
| Funcionalidad evaluada | Inicio de sesión y navegación |
| Cantidad de usuarios simulados | Uso normal |

## Pasos de ejecución

| Paso | Acción |
|---|---|
| 1 | Ingresar al sistema con un usuario válido |
| 2 | Acceder al menú principal |
| 3 | Navegar entre diferentes módulos |
| 4 | Realizar una búsqueda dentro del sistema |
| 5 | Verificar el tiempo de respuesta |

## Resultado esperado

El sistema debe cargar las páginas correctamente, responder rápidamente a las acciones del usuario y mantener estabilidad durante la navegación.

## Resultado obtenido

Pendiente de ejecución.

## Estado

🟡 Pendiente

## Notas / Evidencias

Se agregarán capturas, tiempos de respuesta o registros obtenidos durante la prueba.

---

# Caso de Prueba Negativo

## ID del caso de prueba

TC-014

## Título

Respuesta lenta del sistema ante alta carga de información

## Objetivo

Validar el comportamiento del sistema cuando se realizan operaciones con una cantidad elevada de datos.

## Precondiciones

- El sistema debe contar con información almacenada.
- Debe existir una operación que requiera procesamiento de datos.

## Datos de prueba

| Campo | Valor |
|---|---|
| Cantidad de registros | Alta cantidad de datos |
| Operación realizada | Consulta de información |
| Estado esperado | Mantener funcionamiento |

## Pasos de ejecución

| Paso | Acción |
|---|---|
| 1 | Ingresar al sistema |
| 2 | Acceder a una sección con gran cantidad de registros |
| 3 | Ejecutar una búsqueda o consulta |
| 4 | Observar el tiempo de respuesta |
| 5 | Verificar si existen errores |

## Resultado esperado

El sistema debe controlar la carga de información y evitar bloqueos o fallos durante la operación.

## Resultado obtenido

Pendiente de ejecución.

## Estado

🟡 Pendiente

## Notas / Evidencias

Se registrarán tiempos de respuesta y posibles mensajes de error.
