# ACTIVIDAD EN CLASE GRUPAL: Maquetación de una factura en HTML5

## Estructura del Proyecto

```
PROGRAMACION_PRUEBA01/
├── CLIENTE/                    # Módulo de gestión de clientes
│   ├── index.html              # Formulario principal de cliente
│   └── datos.html              # Página de confirmación de datos
├── Factura/                    # Módulo de facturación
│   ├── index.html              # Formulario de factura
│   └── server.html             # Página de procesamiento
├── FORMULARIO_PRODUCTO/        # Módulo de gestión de productos
│   ├── index.html              # Formulario de productos (cerveza)
│   └── server.html             # Página de procesamiento
├── PRY_FORMULARIO_FCATURA/     # Módulo alternativo de factura
│   ├── index.html              # Formulario cliente-factura
│   └── datos.html              # Página de confirmación
├── Prueba01.txt                # Archivo de pruebas
└── README.md                   # Este archivo
```

## Módulos Disponibles

### 1. CLIENTE
**Propósito**: Formulario completo de registro de clientes
- **Archivo principal**: `CLIENTE/index.html`
- **Funcionalidad**: Captura información básica, contacto y residencia del cliente
- **Campos incluidos**: Nombres, apellidos, fecha de nacimiento, edad, sexo, teléfono, email, dirección completa
- **Página de destino**: `CLIENTE/datos.html`

### 2. Factura
**Propósito**: Sistema de facturación básico
- **Archivo principal**: `Factura/index.html`
- **Funcionalidad**: Muestra una factura con datos de cliente y productos
- **Características**: Incluye cálculo de subtotal, IVA y total
- **Página de destino**: `Factura/server.html`

### 3. FORMULARIO_PRODUCTO
**Propósito**: Registro detallado de productos (especializado en cervezas)
- **Archivo principal**: `FORMULARIO_PRODUCTO/index.html`
- **Funcionalidad**: Formulario completo para productos con características específicas
- **Campos incluidos**: Nombre, precio, descripción, graduación alcohólica, volumen, marca, país de origen, ingredientes, color, temperatura de servicio, disponibilidad, fechas de elaboración y vencimiento, código de barras, stock, proveedor e imagen
- **Página de destino**: `FORMULARIO_PRODUCTO/server.html`

### 4. PRY_FORMULARIO_FCATURA
**Propósito**: Formulario alternativo cliente-factura
- **Archivo principal**: `PRY_FORMULARIO_FCATURA/index.html`
- **Funcionalidad**: Similar al módulo CLIENTE pero con estructura de factura
- **Página de destino**: `PRY_FORMULARIO_FCATURA/datos.html`

## Instrucciones de Ejecución

### Métodos de Ejecución : Ejecución Directa (Recomendado)
1. Navega a la carpeta del proyecto en tu explorador de archivos
2. Haz doble clic en cualquiera de los archivos `index.html` de los módulos
3. El formulario se abrirá automáticamente en tu navegador predeterminado   



