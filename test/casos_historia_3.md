# Casos de Prueba - Sistema Inclusivo

## Historia de Usuario 3: Búsqueda por Cédula

**Módulo:** Consulta de estudiantes  
**Rol involucrado:** Administrador  
**Tipo de prueba:** Prueba funcional

Esta historia valida que el administrador pueda buscar información de estudiantes mediante su número de cédula de manera rápida y eficiente.

---

# Caso de Prueba Positivo

## ID del caso de prueba

TC-005

## Título

Búsqueda exitosa de estudiante mediante número de cédula

## Objetivo

Validar que el administrador pueda consultar correctamente la información de un estudiante registrado utilizando una cédula válida.

## Precondiciones

- El administrador debe haber iniciado sesión.
- Debe existir al menos un estudiante registrado en el sistema.
- El módulo de búsqueda debe estar disponible.

## Datos de prueba

| Campo | Valor |
|---|---|
| Número de cédula | 1723456789 |
| Estado del registro | Estudiante existente |

## Pasos de ejecución

| Paso | Acción |
|---|---|
| 1 | Ingresar al sistema con usuario administrador |
| 2 | Acceder al módulo de búsqueda de estudiantes |
| 3 | Ingresar una cédula válida |
| 4 | Presionar el botón "Buscar" |
| 5 | Revisar la información mostrada |

## Resultado esperado

El sistema debe encontrar al estudiante correspondiente y mostrar su información registrada correctamente.

## Resultado obtenido

Pendiente de ejecución.

## Estado

🟡 Pendiente

## Notas / Evidencias

Se agregará captura del resultado de búsqueda.

---

# Caso de Prueba Negativo

## ID del caso de prueba

TC-006

## Título

Búsqueda de estudiante con cédula inexistente

## Objetivo

Validar que el sistema controle correctamente la búsqueda cuando la cédula ingresada no pertenece a ningún estudiante registrado.

## Precondiciones

- El administrador debe haber iniciado sesión.
- El módulo de búsqueda debe estar disponible.

## Datos de prueba

| Campo | Valor |
|---|---|
| Número de cédula | 9999999999 |
| Estado del registro | No existente |

## Pasos de ejecución

| Paso | Acción |
|---|---|
| 1 | Acceder al módulo de búsqueda |
| 2 | Ingresar una cédula inexistente |
| 3 | Presionar el botón "Buscar" |
| 4 | Revisar la respuesta del sistema |

## Resultado esperado

El sistema debe mostrar un mensaje informativo indicando que no se encontraron registros asociados a la cédula ingresada.

## Resultado obtenido

Pendiente de ejecución.

## Estado

🟡 Pendiente

## Notas / Evidencias

Se agregará captura del mensaje mostrado por el sistema.
