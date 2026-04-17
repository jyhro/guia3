# App de Presupuestos

## **HTML Issues**

### HTML: Estructura base del HTML

**Descripción:**
Crear el archivo `index.html` con la estructura base del documento.

**Precondición:**

* [x] Repositorio creado
* [x] Estructura de carpetas definida

**Postcondición:**

* [x] Archivo HTML funcional con `<head>` y `<body>`
* [x] Conexión a CSS y JS

**Criterios de aceptación:**

* [x] Incluye `<meta>`, `<title>`
* [x] Link correcto a `/assets/styles/styles.css`
* [x] Script a `/js/app.js`

**Pruebas:**

* [x] Abrir en navegador sin errores
* [x] Verificar carga de CSS y JS en DevTools

### HTML: Formulario de transacciones

**Descripción:**
Crear formulario con inputs:

* [x] monto
* [x] tipo (ingreso/gasto)
* [x] descripción

**Precondición:**

* [x] Issue [#3](https://github.com/jyhro/guia3/issues/3) completado

**Postcondición:**

* [x] Formulario visible y usable

**Criterios de aceptación:**

* [x] Inputs con `id`
* [x] Botón submit presente

**Pruebas:**

* [x] Validar que los campos existan
* [x] Probar escritura en inputs

### HTML: Contenedor de lista de transacciones

**Descripción:**
Crear estructura para mostrar transacciones (tabla o lista).

**Precondición:**

* [x] Issue [#4](https://github.com/jyhro/guia3/issues/4) completado

**Postcondición:**

* [x] Contenedor visible vacío

**Criterios de aceptación:**

* [x] Elemento con `id="transaction-list"`

**Pruebas:**

* [x] Verificar render en navegador

### HTML: Sección de resumen

**Descripción:**
Crear sección que muestre:

* [x] ingresos
* [x] gastos
* [x] saldo

**Precondición:**

* [x] Issue [#3](https://github.com/jyhro/guia3/issues/3) completado

**Postcondición:**

* [x] Sección visible con placeholders

**Criterios de aceptación:**

* [x] IDs: `income`, `expense`, `balance`

**Pruebas:**

* [x] Verificar visibilidad y estructura

---

## CSS Issues

### CSS: Reset y estilos globales

**Descripción:**
Aplicar estilos base:

* [x] reset
* [x] tipografía
* [x] layout general

**Precondición:**

* [x] HTML base listo

**Postcondición:**

* [x] Diseño consistente

**Criterios de aceptación:**

* [x] Uso de `box-sizing`
* [x] Fuente definida

**Pruebas:**

* [x] Ver consistencia visual

### CSS: Estilos del formulario

**Descripción:**
Estilizar inputs y botón.

**Precondición:**

* [x] Formulario creado

**Postcondición:**

* [x] Formulario usable y claro

**Criterios de aceptación:**

* [x] Inputs alineados
* [x] Botón con hover

**Pruebas:**

* [x] Probar interacción visual

### CSS: Estilos de lista de transacciones

**Descripción:**
Estilizar lista o tabla.

**Precondición:**

* [x] Contenedor creado

**Postcondición:**

* [x] Lista legible

**Criterios de aceptación:**

* [x] Diferenciar ingresos/gastos (colores)

**Pruebas:**

* [x] Insertar datos dummy y validar estilos

### CSS: Estilos del resumen

**Descripción:**
Diseñar sección de totales.

**Precondición:**

* [x] HTML resumen listo

**Postcondición:**

* [x] Resumen destacado visualmente

**Criterios de aceptación:**

* [x] Tipografía clara
* [x] Colores diferenciados

**Pruebas:**

* [x] Validar legibilidad

### CSS: Responsividad

**Descripción:**
Adaptar diseño a móviles.

**Precondición:**

* [x] Estilos base completos

**Postcondición:**

* [x] App usable en móvil

**Criterios de aceptación:**

* [x] Uso de media queries

**Pruebas:**

* [x] DevTools modo responsive

---

## JavaScript Issues

### JS: Captura de datos del formulario

**Descripción:**
Capturar datos al enviar el formulario.

**Precondición:**

* [ ] Formulario funcional

**Postcondición:**

* [ ] Datos disponibles en JS

**Criterios de aceptación:**

* [ ] Uso de `addEventListener`

**Pruebas:**

* [ ] Console.log de datos

### JS: Crear transacción

**Descripción:**
Agregar transacción al DOM.

**Precondición:**

* Issue [#13](https://github.com/jyhro/guia3/issues/13) listo

**Postcondición:**

* [ ] Transacción visible en lista

**Criterios de aceptación:**

* [ ] Render dinámico correcto

**Pruebas:**

* [ ] Agregar múltiples transacciones

### JS: Eliminar transacción

**Descripción:**
Eliminar transacción del DOM.

**Precondición:**

* [ ] Lista funcional

**Postcondición:**

* [ ] Eliminación correcta

**Criterios de aceptación:**

* [ ] Botón eliminar por item

**Pruebas:**

* [ ] Eliminar varias transacciones

### JS: Cálculo de totales

**Descripción:**
Calcular ingresos, gastos y saldo.

**Precondición:**

* [ ] Transacciones existentes

**Postcondición:**

* [ ] Totales correctos

**Criterios de aceptación:**

* [ ] Actualización automática

**Pruebas:**

* [ ] Validar cálculos manualmente

### JS: Actualizar UI del resumen

**Descripción:**
Mostrar totales en pantalla.

**Precondición:**

* [ ] Issue [#16](https://github.com/jyhro/guia3/issues/16) listo

**Postcondición:**

* [ ] UI sincronizada

**Criterios de aceptación:**

* [ ] Cambios en DOM correctos

**Pruebas:**

* [ ] Verificar valores en pantalla

### JS: Persistencia con localStorage

**Descripción:**

Guardar y recuperar datos.

**Precondición:**

* [ ] CRUD funcional

**Postcondición:**

* [ ] Datos persistentes

**Criterios de aceptación:**

* [ ] Uso de `localStorage.setItem/getItem`

**Pruebas:**

* [ ] Recargar página y validar datos

### JS: Cargar datos al iniciar

**Descripción:**
Renderizar datos guardados al cargar.

**Precondición:**

* [ ] localStorage implementado

**Postcondición:**

* [ ] Datos visibles al iniciar

**Criterios de aceptación:**

* [ ] Render automático

**Pruebas:**

* [ ] Refrescar navegador

## **Testing / Integración**

### TEST: Pruebas de integración

**Descripción:**
Validar flujo completo.

**Precondición:**

* [ ] Todas las features completas

**Postcondición:**

* [ ] App funcional

**Criterios de aceptación:**

* [ ] Flujo completo sin errores

**Pruebas:**

* [ ] Crear → eliminar → recargar → validar persistencia

### JS: Manejo de errores

**Labels:** `javascript`, `enhancement`

**Descripción:**
Validar inputs.

**Precondición:**

* [ ] Formulario funcional

**Postcondición:**

* [ ] Errores controlados

**Criterios de aceptación:**

* [ ] No permitir campos vacíos

**Pruebas:**

* [ ] Intentar enviar vacío
