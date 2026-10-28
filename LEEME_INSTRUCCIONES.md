# 🏋️‍♂️ BOCETO WEB Y GUÍA DE MODIFICACIÓN EN VIVO - JEMA MARKET S.A.S.

¡Bienvenido(a)! Esta carpeta contiene el **boceto interactivo 100% en HTML y CSS** para presentarle a la clienta el diseño de la tienda virtual de suplementos deportivos, inspirado en la estética limpia, moderna y visual de `Frontend_EcoRisaralda`, pero adaptado a la marca **JEMA Market S.A.S.** con su paleta de colores oficial.

---

## 🎨 CÓMO MODIFICAR COLORES EN VIVO (PARA TU COMPAÑERA)

La estructura está organizada de manera muy sencilla para que cualquier cambio de color se aplique de inmediato a todas las pantallas:

1. Ve a la carpeta **`estilos`** y abre el archivo **`colores.css`** con tu editor favorito (Bloc de Notas, VS Code, Cursor, etc.).
2. En la parte superior verás las variables de color con comentarios en español:
   ```css
   :root {
     --color-marino-oscuro: #0A3A6A;   /* Azul marino de encabezados y logo */
     --color-azul-vibrante: #0870C8;   /* Azul de botones principales y enlaces */
     --color-celeste-acento:#17BFF5;   /* Celeste llamativo para insignias y detalles */
     --color-celeste-suave: #EAF6FE;   /* Fondo suave para tarjetas y secciones */
     --color-exito:         #059669;   /* Verde para: Contra Entrega, Pagado */
     ...
   }
   ```
3. **Cambia cualquier código de color (hexadecimal)**, guarda el archivo (`Ctrl + S`) y **recarga la página en tu navegador (`F5`)**. ¡Verás los cambios en vivo en todas las páginas!

---

## 📂 PANTALLAS CREADAS EN ESTE BOCETO

Puedes hacer doble clic en cualquiera de estos archivos para abrirlos en Google Chrome, Edge o tu navegador preferido:

| Archivo | Descripción de la Pantalla |
| :--- | :--- |
| **`index.html`** | **Página de Inicio (Home):** Hero banner con degradado, tarjetas flotantes de confianza, beneficios, franja informativa de pago contra entrega, suplementos destacados y pie de página completo. |
| **`catalogo.html`** | **Catálogo de Suplementos:** Filtros laterales por categoría, marca y contra entrega, barra superior y rejilla de productos. |
| **`producto-detalle.html`** | **Ficha de Producto:** Vista detallada del suplemento, selección de sabores (chocolate, vainilla, fresa), selección de tamaños, cálculo de ahorro y botón directo a Contra Entrega. |
| **`carrito.html`** | **Carrito de Compras:** Lista de suplementos agregados, control de cantidades, subtotal y resumen de compra. |
| **`checkout.html`** | **Finalizar Pedido:** Formulario de envío para Colombia, selector de método de pago destacando **Pago Contra Entrega** y dejando la pasarela en línea como "Próximamente" (según requerimiento de permisos pendientes). |
| **`admin.html`** | **Panel de Gestión y Empleados:** Dashboard con métricas clave, alertas de stock bajo, tabla operativa para confirmar pedidos contra entrega y nota de arquitectura escalable. |
| **`login.html`** | **Acceso al Sistema:** Pantalla con diseño en degradado oscuro estilo *EcoRisaralda*, pensada para los 3 roles (Admin, Empleado y Cliente). |

---

## 📦 UBICACIÓN DE LOS ARCHIVOS
`C:\Users\USUARIO\Documents\JEMA-Market-Boceto\`

Cualquier duda o ajuste adicional, todo el código está comentado en español y sin librerías complejas.
