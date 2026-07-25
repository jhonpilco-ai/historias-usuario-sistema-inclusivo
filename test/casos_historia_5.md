# Casos de Prueba - Sistema Inclusivo

## Historia de Usuario 5: Lectura de Contenido

**Módulo:** Accesibilidad y visualización de contenido  
**Rol involucrado:** Usuario  
**Tipo de prueba:** Prueba funcional

Esta historia valida que los usuarios puedan acceder al contenido del sistema de forma clara, legible y accesible mediante las herramientas de lectura disponibles.

---

# Caso de Prueba Positivo

## ID del caso de prueba

TC-009

## Título

Visualización correcta del contenido mediante herramientas de lectura

## Objetivo

Validar que el usuario pueda acceder y visualizar correctamente la información presentada por el sistema.

## Precondiciones

- El usuario debe poder acceder al sistema.
- Debe existir contenido disponible para visualizar.
- El navegador debe permitir la carga correcta de la interfaz.

## Datos de prueba

| Campo | Valor |
|---|---|
| Usuario | Usuario registrado |
| Contenido seleccionado | Información de actividad inclusiva |
| Dispositivo | Computador de escritorio |

## Pasos de ejecución

| Paso | Acción |
|---|---|
| 1 | Ingresar al sistema |
| 2 | Acceder a una sección con información disponible |
| 3 | Activar la herramienta de lectura de contenido |
| 4 | Revisar la presentación de la información |
| 5 | Verificar la legibilidad del contenido |

## Resultado esperado

El contenido debe mostrarse correctamente, con una estructura clara y accesible para el usuario.

## Resultado obtenido

Pendiente de ejecución.

## Estado

🟡 Pendiente

## Notas / Evidencias

Se agregarán capturas mostrando la visualización del contenido.

---

# Caso de Prueba Negativo

## ID del caso de prueba

TC-010

## Título

Visualización incorrecta de contenido con información no disponible

## Objetivo

Validar que el sistema controle adecuadamente cuando el contenido solicitado no existe o no puede cargarse.

## Precondiciones

- El usuario debe ingresar al sistema.
- Debe existir una sección sin información disponible para realizar la prueba.

## Datos de prueba

| Campo | Valor |
|---|---|
| Contenido solicitado | Información inexistente |
| Estado | No disponible |

## Pasos de ejecución

| Paso | Acción |
|---|---|
| 1 | Ingresar al sistema |
| 2 | Acceder a una sección sin contenido |
| 3 | Intentar visualizar la información |
| 4 | Revisar la respuesta mostrada |

## Resultado esperado

El sistema debe mostrar un mensaje informativo indicando que no existe contenido disponible y mantener una interfaz correcta.

## Resultado obtenido

Pendiente de ejecución.

## Estado

🟡 Pendiente

## Notas / Evidencias

Se agregará captura del mensaje mostrado por el sistema.
