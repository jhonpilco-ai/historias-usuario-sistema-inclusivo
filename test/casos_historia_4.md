# Casos de Prueba - Sistema Inclusivo

## Historia de Usuario 4: Reportes en Excel

**Módulo:** Reportes del sistema  
**Rol involucrado:** Administrador  
**Tipo de prueba:** Prueba funcional

Esta historia valida la generación y descarga de reportes en formato Excel con información actualizada del sistema.

---

# Caso de Prueba Positivo

## ID del caso de prueba

TC-007

## Título

Generación exitosa de reporte en formato Excel

## Objetivo

Validar que el administrador pueda generar un archivo Excel con información correcta del sistema.

## Precondiciones

- El administrador debe haber iniciado sesión.
- Deben existir datos registrados en el sistema.
- El módulo de reportes debe estar habilitado.

## Datos de prueba

| Campo | Valor |
|---|---|
| Tipo de reporte | Listado de estudiantes inscritos |
| Formato generado | Excel (.xlsx) |
| Datos disponibles | Registros existentes |

## Pasos de ejecución

| Paso | Acción |
|---|---|
| 1 | Ingresar al sistema como administrador |
| 2 | Acceder al módulo de reportes |
| 3 | Seleccionar el tipo de reporte requerido |
| 4 | Presionar la opción "Generar Excel" |
| 5 | Descargar el archivo generado |
| 6 | Abrir el documento para verificar la información |

## Resultado esperado

El sistema debe generar correctamente el archivo Excel, permitiendo su descarga y mostrando información actualizada.

## Resultado obtenido

Pendiente de ejecución.

## Estado

🟡 Pendiente

## Notas / Evidencias

Se agregará captura del archivo generado y su contenido.

---

# Caso de Prueba Negativo

## ID del caso de prueba

TC-008

## Título

Generación de reporte sin información disponible

## Objetivo

Validar que el sistema responda correctamente cuando no existen datos para generar un reporte.

## Precondiciones

- El administrador debe acceder al módulo de reportes.
- El sistema debe encontrarse sin registros disponibles.

## Datos de prueba

| Campo | Valor |
|---|---|
| Tipo de reporte | Listado de estudiantes |
| Información disponible | Sin registros |

## Pasos de ejecución

| Paso | Acción |
|---|---|
| 1 | Ingresar al módulo de reportes |
| 2 | Seleccionar un reporte |
| 3 | Intentar generar el archivo Excel |
| 4 | Revisar la respuesta del sistema |

## Resultado esperado

El sistema debe informar que no existen datos disponibles y evitar generar un archivo vacío o incorrecto.

## Resultado obtenido

Pendiente de ejecución.

## Estado

🟡 Pendiente

## Notas / Evidencias

Se agregará captura del mensaje mostrado por el sistema.
