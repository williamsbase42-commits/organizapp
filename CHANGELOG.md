# Changelog - OrganizApp

Todas las mejoras y correcciones notables de este proyecto serán documentadas en este archivo.

## [1.0.2] - 2025-01-27

### 🐛 Correcciones
- **Menú de opciones en carpetas**: Arreglado el problema donde los menús de tres puntos de elementos dentro de carpetas no se mostraban correctamente
- **Posición de botones modales**: Corregida la disposición de botones en el modal de nuevo elemento (cancelar a la izquierda, agregar a la derecha)
- **Visibilidad del FAB**: Solucionado el problema donde el botón flotante "+" no aparecía dentro de las carpetas creadas

### 🔧 Mejoras técnicas
- Agregados estilos CSS específicos para menús de opciones dentro de carpetas
- Configurado `overflow: visible` en todos los contenedores relevantes para evitar cortes de menús
- Mejorado el sistema de visibilidad del FAB para mantenerlo visible en todas las vistas de carpetas
- Actualizada la función `handleScrollVisibility()` para no ocultar el FAB en vista de carpetas
- Agregadas llamadas a `ensureFabVisibility()` en funciones de navegación de carpetas

### 📱 PWA
- Actualizado Service Worker a versión v1.0.2
- Actualizado manifest.json con nueva versión
- Mejorado el sistema de detección de actualizaciones

## [1.0.1] - Versión inicial
- Lanzamiento inicial de OrganizApp
- Funcionalidades básicas de gestión de tareas, notas, compras y recordatorios
- Sistema de carpetas implementado
- PWA completamente funcional
- Modo oscuro automático
- Vista de calendario
- Búsqueda en tiempo real

---

### Formato del Changelog
- **🐛 Correcciones**: Cambios que corrigen problemas
- **✨ Nuevas características**: Nuevas funcionalidades añadidas
- **🔧 Mejoras técnicas**: Mejoras en el código sin cambios visibles al usuario
- **📱 PWA**: Cambios relacionados con la funcionalidad PWA
- **⚡ Rendimiento**: Mejoras de rendimiento
- **🔒 Seguridad**: Cambios relacionados con seguridad
