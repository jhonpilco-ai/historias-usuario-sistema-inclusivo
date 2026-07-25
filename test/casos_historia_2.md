# Casos de Prueba - Sistema Inclusivo

## Historia de Usuario 2: Inscripción de Estudiantes

**Módulo:** Inscripción de estudiantes  
**Rol involucrado:** Estudiante  
**Tipo de prueba:** Prueba funcional

Esta historia valida que los estudiantes puedan registrarse en actividades disponibles dentro del sistema.

---

# Caso de Prueba Positivo

## ID del caso de prueba

TC-003

## Título

Inscripción exitosa de estudiante en una actividad

## Objetivo

Validar que un estudiante pueda completar correctamente el proceso de inscripción a una actividad disponible.

## Precondiciones

- El estudiante debe estar registrado en el sistema.
- Deben existir actividades disponibles.
- El sistema debe encontrarse operativo.

## Datos de prueba

| Campo | Valor |
|---|---|
| Nombre estudiante | María López |
| Cédula | 1723456789 |
| Correo | maria.lopez@gmail.com |
| Actividad seleccionada | Taller de Inclusión Digital |

## Pasos de ejecución

| Paso | Acción |
|---|---|
| 1 | Ingresar al sistema como estudiante |
| 2 | Consultar las actividades disponibles |
| 3 | Seleccionar una actividad |
| 4 | Completar el formulario de inscripción |
| 5 | Confirmar la inscripción |
| 6 | Verificar el registro realizado |

## Resultado esperado

El sistema debe registrar correctamente la inscripción del estudiante y mostrar un mensaje de confirmación.

## Resultado obtenido

Pendiente de ejecución.

## Estado

🟡 Pendiente

## Notas / Evidencias

Se agregarán capturas del formulario y confirmación de inscripción.

---

# Caso de Prueba Negativo

## ID del caso de prueba

TC-004

## Título

Inscripción rechazada por información incompleta

## Objetivo

Validar que el sistema no permita registrar estudiantes cuando faltan datos obligatorios.

## Precondiciones

- El estudiante debe acceder al formulario de inscripción.
- Debe existir una actividad disponible.

## Datos de prueba

| Campo | Valor |
|---|---|
| Nombre estudiante | María López |
| Cédula | Vacío |
| Correo | maria.lopez@gmail.com |
| Actividad | Taller de Inclusión Digital |

## Pasos de ejecución

| Paso | Acción |
|---|---|
| 1 | Acceder al formulario de inscripción |
| 2 | Seleccionar una actividad |
| 3 | Completar parcialmente la información |
| 4 | Presionar el botón de inscripción |
| 5 | Revisar la respuesta del sistema |

## Resultado esperado

El sistema debe indicar que faltan datos obligatorios y debe evitar guardar la inscripción.

## Resultado obtenido

Pendiente de ejecución.

## Estado

🟡 Pendiente

## Notas / Evidencias

Se agregarán capturas del mensaje de validación.
