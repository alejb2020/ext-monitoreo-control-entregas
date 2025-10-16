# Monitoreo - Control de Entregas

Una extensión de navegador universal que extrae y organiza datos de monitoreo de entregas desde la plataforma de administración de MercadoLibre. Compatible con Chrome, Edge, Brave, Firefox y Opera.

## 🎯 Funcionalidad Principal

Esta extensión toma los datos de la página de monitoreo de distribución y los presenta en una tabla organizada y fácil de usar, permitiendo:

- **Extracción automática** de datos de rutas, drivers, entregas y métricas
- **Organización estructurada** en formato de tabla para Excel o Google Sheet
- **Copia directa** al portapapeles en formato compatible con hojas de cálculo

## 📊 Datos Extraídos

La extensión extrae y organiza la siguiente información:

| Campo | Descripción |
|-------|-------------|
| **Ruta** | Identificador de la ruta (A1, A2, B1, etc.) |
| **Nombre** | Nombre del driver asignado |
| **Patente** | Patente del vehículo |
| **ID Ruta** | Número único de identificación de la ruta |
| **Entregados** | Cantidad de paquetes entregados exitosamente |
| **Fallidos** | Cantidad de paquetes no entregados |
| **Fecha** | Fecha actual del monitoreo |
| **Horas** | Tiempo transcurrido en horas |
| **Minutos** | Tiempo transcurrido en minutos |

## 🚀 Características Principales

### Actualización de Datos
- **Botón "Actualizar"**: Refresca los datos con la información más reciente de la página

### Organización Inteligente
- **Ordenamiento automático**: Al actualizar, ordena automáticamente por rutas (A1, A2, A3, B1, B2, etc.)
- **Ordenamiento manual**: Permite ordenar por cualquier columna (ascendente/descendente)
- **Ordenamiento numérico**: Las rutas se ordenan correctamente por letra y número

### Exportación de Datos
- **Botón "Copiar"**: Copia solo los datos (sin encabezados) al portapapeles
- **Botón "Actualizar y Copiar"**: Combina actualización y copia en una sola acción
- **Formato Excel**: Datos separados por tabs, listos para pegar en Excel

### Navegación
- **Botón "Ir a tabla"**: Scroll rápido a la sección de control
- **Botón "Ir al inicio"**: Regresa al inicio de la página

## 🛠️ Instalación

### Para Chrome, Edge, Brave y Opera:
1. Descarga o clona este repositorio
2. Abre tu navegador y ve a:
   - **Chrome**: `chrome://extensions/`
   - **Edge**: `edge://extensions/`
   - **Brave**: `brave://extensions/`
   - **Opera**: `opera://extensions/`
3. Activa el "Modo de desarrollador" o "Developer mode"
4. Haz clic en "Cargar extensión sin empaquetar" o "Load unpacked"
5. Selecciona la carpeta que contiene los archivos de la extensión

### Para Firefox:
1. Descarga o clona este repositorio
2. Abre Firefox y ve a `about:debugging`
3. Haz clic en "Este Firefox" en el panel izquierdo
4. Haz clic en "Cargar complemento temporal"
5. Selecciona el archivo `manifest.json` de la extensión

## 📝 Uso

1. **Navega** a la página de monitoreo de distribución de MercadoLibre
2. **La tabla se genera automáticamente** al cargar la página
3. **Usa los botones de control** para:
   - Actualizar datos en tiempo real
   - Copiar información al portapapeles
   - Combinar ambas acciones
4. **Ordena manualmente** haciendo clic en cualquier encabezado de columna
5. **Navega fácilmente** con los botones flotantes

## 🎯 Casos de Uso

- **Análisis de rendimiento**: Revisar entregas por chofer o ruta
- **Reportes diarios**: Exportar datos para informes de gestión
- **Seguimiento en tiempo real**: Monitorear el progreso durante el día
- **Análisis de eficiencia**: Comparar tiempos y tasas de entrega

## 🔧 Compatibilidad

- **Navegadores**: 
  - ✅ Chrome (Manifest V3)
  - ✅ Microsoft Edge (Chromium-based)
  - ✅ Brave Browser
  - ✅ Opera
  - ✅ Firefox (WebExtensions API)
- **Sistemas operativos**: Windows, macOS, Linux

## 📋 Archivos Incluidos

- `manifest.json` - Configuración de la extensión
- `content.js` - Lógica principal y funcionalidad
- `styles.css` - Estilos y diseño de la interfaz

## 🚨 Limitaciones

- Solo funciona en la página específica de monitoreo de distribución
- Requiere que la página esté completamente cargada para funcionar correctamente
- Los datos se extraen del DOM actual de la página

## 📝 Notas Importantes

### Diferencias entre Navegadores:
- **Chrome/Edge/Brave/Opera**: Usan Manifest V3, completamente compatibles
- **Firefox**: Usa WebExtensions API, compatible pero con algunas diferencias menores en permisos

---

**Desarrollado por**: Alejandro Baez (SVI1 Villa Maria)  
**Versión**: 1.0
