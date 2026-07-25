# Casos de Prueba - Sistema Inclusivo

## Historia de Usuario 8: Navegación por Teclado

**Módulo:** Accesibilidad del sistema  
**Rol involucrado:** Usuario  
**Tipo de prueba:** Prueba de accesibilidad

Esta historia valida que los usuarios puedan navegar por el sistema utilizando únicamente el teclado, facilitando el acceso a personas con diferentes necesidades de interacción.

---

# Caso de Prueba Positivo

## ID del caso de prueba

TC-015

## Título

Navegación completa mediante teclado

## Objetivo

Validar que los elementos interactivos del sistema puedan utilizarse mediante teclado sin necesidad de utilizar el mouse.

## Precondiciones

- El sistema debe estar disponible.
- Debe existir una interfaz con formularios y botones.
- El usuario debe poder acceder al sistema.

## Datos de prueba

| Campo | Valor |
|---|---|
| Método de navegación | Teclado |
| Tecla principal utilizada | Tab |
| Elementos evaluados | Formularios y botones |

## Pasos de ejecución

| Paso | Acción |
|---|---|
| 1 | Abrir la aplicación |
| 2 | Navegar utilizando únicamente la tecla Tab |
| 3 | Verificar que los elementos reciban selección |
| 4 | Completar un formulario mediante teclado |
| 5 | Activar botones utilizando teclado |

## Resultado esperado

Todos los elementos interactivos deben poder seleccionarse y utilizarse correctamente mediante teclado, siguiendo un orden lógico.

## Resultado obtenido

Pendiente de ejecución.

## Estado

🟡 Pendiente

## Notas / Evidencias

Se agregarán capturas mostrando la navegación mediante teclado.

---

# Caso de Prueba Negativo

## ID del caso de prueba

TC-016

## Título

Elemento no accesible mediante navegación por teclado

## Objetivo

Validar que el sistema pueda identificar problemas de accesibilidad cuando algún elemento no permite interacción mediante teclado.

## Precondiciones

- El usuario debe encontrarse dentro del sistema.
- Debe existir una interfaz con elementos interactivos.

## Datos de prueba

| Campo | Valor |
|---|---|
| Método utilizado | Teclado |
| Acción evaluada | Navegación con tecla Tab |
| Elemento probado | Botón o formulario |

## Pasos de ejecución

| Paso | Acción |
|---|---|
| 1 | Abrir la aplicación |
| 2 | Intentar desplazarse por la interfaz usando Tab |
| 3 | Revisar cada elemento interactivo |
| 4 | Identificar elementos que no reciben selección |

## Resultado esperado

El sistema debe permitir la navegación completa mediante teclado o mostrar elementos correctamente identificados para corregir problemas de accesibilidad.

## Resultado obtenido

Pendiente de ejecución.

## Estado

🟡 Pendiente

## Notas / Evidencias

Se agregará evidencia del elemento que presente problemas de accesibilidad.
