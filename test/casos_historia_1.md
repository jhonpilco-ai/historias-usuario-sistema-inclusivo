# Casos de Prueba - Sistema Inclusivo

## Historia de Usuario 1: Gestión de Actividades

**Módulo:** Administración de actividades  
**Rol involucrado:** Administrador  
**Tipo de prueba:** Prueba funcional

Esta historia de usuario valida la capacidad del administrador para crear, editar y eliminar actividades inclusivas dentro del sistema.

---

# Caso de Prueba Positivo

## ID del caso de prueba

TC-001

## Título

Creación exitosa de una actividad inclusiva

## Objetivo

Validar que el administrador pueda crear una nueva actividad ingresando correctamente todos los datos requeridos.

## Precondiciones

- El administrador debe tener una cuenta registrada.
- El administrador debe haber iniciado sesión.
- El usuario debe contar con permisos para gestionar actividades.
- El sistema debe estar disponible.

## Datos de prueba

| Campo | Valor |
|---|---|
| Nombre de actividad | Taller de Inclusión Digital |
| Descripción | Capacitación sobre herramientas tecnológicas |
| Fecha | 10/08/2026 |
| Cupos disponibles | 30 |

## Pasos de ejecución

| Paso | Acción |
|---|---|
| 1 | Ingresar al sistema con una cuenta de administrador |
| 2 | Acceder al módulo de gestión de actividades |
| 3 | Seleccionar la opción "Crear actividad" |
| 4 | Completar todos los campos obligatorios |
| 5 | Presionar el botón "Guardar" |
| 6 | Verificar que la actividad aparezca registrada |

## Resultado esperado

El sistema debe guardar la nueva actividad correctamente y mostrarla dentro del listado de actividades disponibles.

## Resultado obtenido

Pendiente de ejecución.

## Estado

🟡 Pendiente

## Notas / Evidencias

Se agregarán capturas de pantalla o evidencias después de ejecutar la prueba.

---

# Caso de Prueba Negativo

## ID del caso de prueba

TC-002

## Título

Creación de actividad con campos obligatorios incompletos

## Objetivo

Validar que el sistema impida registrar actividades cuando la información requerida no está completa.

## Precondiciones

- El administrador debe haber iniciado sesión.
- Debe encontrarse dentro del formulario de creación de actividades.

## Datos de prueba

| Campo | Valor |
|---|---|
| Nombre de actividad | Vacío |
| Descripción | Actividad inclusiva |
| Fecha | 10/08/2026 |
| Cupos disponibles | 30 |

## Pasos de ejecución

| Paso | Acción |
|---|---|
| 1 | Ingresar al módulo de actividades |
| 2 | Seleccionar "Crear actividad" |
| 3 | Dejar vacío un campo obligatorio |
| 4 | Presionar el botón "Guardar" |
| 5 | Revisar la respuesta del sistema |

## Resultado esperado

El sistema debe mostrar un mensaje indicando que existen campos obligatorios pendientes y no debe guardar la actividad.

## Resultado obtenido

Pendiente de ejecución.

## Estado

🟡 Pendiente

## Notas / Evidencias

Se agregarán capturas o mensajes de validación del sistema.
