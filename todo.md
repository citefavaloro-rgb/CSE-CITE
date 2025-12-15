# SGE-CITE - Lista de Funcionalidades

## Backend - Base de Datos y Esquemas
- [x] Diseñar esquema de tabla students (estudiantes)
- [x] Diseñar esquema de tabla subjects (materias por estudiante)
- [x] Diseñar esquema de tabla authorized_persons (personas autorizadas para retiro)
- [x] Diseñar esquema de tabla documents (documentos adjuntos)
- [x] Diseñar esquema de tabla courses (cursos/divisiones)
- [x] Ejecutar migración de base de datos con pnpm db:push

## Backend - Helpers de Base de Datos
- [x] Implementar helpers para estudiantes (crear, actualizar, listar, buscar)
- [x] Implementar helpers para materias (agregar, actualizar, eliminar)
- [x] Implementar helpers para personas autorizadas (CRUD completo)
- [x] Implementar helpers para documentos (subir, listar, eliminar)
- [x] Implementar helpers para estadísticas y reportes

## Backend - Procedimientos tRPC
- [x] Crear procedimientos para gestión de estudiantes (list, get, create, update, delete)
- [x] Crear procedimientos para filtros y búsquedas avanzadas
- [x] Crear procedimientos para gestión de legajos individuales
- [x] Crear procedimientos para personas autorizadas (CRUD)
- [x] Crear procedimientos para carga masiva desde Excel
- [x] Crear procedimientos para generación de reportes PDF
- [x] Crear procedimientos para generación de reportes Excel
- [x] Crear procedimientos para subida de documentos a S3
- [x] Crear procedimientos para notificaciones automáticas
- [x] Crear procedimientos para estadísticas del dashboard

## Backend - Integraciones
- [x] Integrar almacenamiento S3 para documentos adjuntos
- [x] Implementar parser de archivos Excel con validación
- [x] Implementar generador de PDFs con estadísticas
- [x] Implementar generador de archivos Excel para reportes
- [x] Configurar sistema de notificaciones al coordinador

## Frontend - Dashboard Principal
- [x] Crear página de Dashboard con layout principal
- [x] Implementar tarjetas de estadísticas generales
- [x] Agregar gráficos de rendimiento académico
- [x] Mostrar alertas de alumnos en riesgo

## Frontend - Gestión de Estudiantes
- [x] Crear página de listado de estudiantes con tabla completa
- [x] Implementar sistema de filtros (año, división, turno)
- [x] Implementar búsqueda por nombre y DNI
- [x] Agregar ordenamiento alfabético y por otros criterios
- [x] Implementar paginación de resultados
- [x] Agregar botones de acciones (ver, editar, eliminar)

## Frontend - Legajo Individual
- [x] Crear página de legajo individual del alumno
- [x] Mostrar datos personales completos
- [x] Mostrar historial académico por año
- [x] Mostrar materias pendientes, recursadas e intensificadas
- [x] Agregar sección de documentos adjuntos
- [x] Implementar edición de datos del alumno

## Frontend - Personas Autorizadas
- [x] Crear componente de lista de personas autorizadas
- [x] Implementar formulario de agregar autorizado
- [x] Implementar edición de autorizados
- [x] Implementar eliminación de autorizados
- [x] Agregar validación de campos obligatorios

## Frontend - Carga Masiva
- [x] Crear página de carga masiva de datos
- [x] Implementar selector de archivo Excel
- [x] Mostrar preview de datos antes de importar
- [x] Implementar validación de datos
- [x] Mostrar errores y advertencias de importación
- [x] Agregar confirmación antes de guardar

## Frontend - Reportes
- [x] Crear página de generación de reportes
- [x] Implementar selector de tipo de reporte (PDF/Excel)
- [x] Agregar filtros para reportes personalizados
- [x] Implementar descarga de reportes generados

## Frontend - Responsive y UX
- [x] Optimizar tabla de estudiantes para móviles
- [x] Optimizar formularios para pantallas pequeñas
- [x] Optimizar legajo individual para móviles
- [x] Agregar menú de navegación responsive
- [x] Implementar estados de carga en todas las operaciones
- [x] Agregar mensajes de éxito/error con toast

## Sistema de Autenticación y Permisos
- [x] Configurar roles de coordinador CITE (admin) y preceptores (user)
- [x] Implementar restricciones de acceso por rol
- [ ] Crear sistema de enlaces compartibles para preceptores

## Testing y Validación
- [x] Escribir tests para procedimientos de estudiantes
- [x] Escribir tests para carga masiva de Excel
- [x] Escribir tests para generación de reportes
- [x] Escribir tests para sistema de notificaciones
- [x] Validar funcionamiento en dispositivos móviles

## Documentación y Entrega
- [x] Crear checkpoint final del proyecto
- [x] Preparar documentación de uso para coordinador
- [x] Preparar documentación de uso para preceptores


## Sistema de Asistencias - Fase 2

### Backend
- [x] Actualizar esquema de base de datos con tablas de asistencias
- [x] Implementar helpers de base de datos para asistencias
- [x] Crear procedimientos tRPC para gestión de asistencias
- [x] Implementar notificaciones automáticas de inasistencias

### Frontend
- [x] Desarrollar interfaz para registrar asistencias diarias
- [x] Crear página de reportes de ausentismo por estudiante
- [x] Crear página de reportes de ausentismo por curso
- [x] Optimizar interfaz para dispositivos móviles

### Testing
- [x] Escribir tests para sistema de asistencias
- [x] Crear checkpoint final con asistencias


## Sistema de Importación de Asistencias - Fase 3

### Backend
- [x] Crear utilidad para parsear archivos Excel de asistencias
- [x] Implementar procedimientos tRPC para importación de asistencias
- [x] Validar datos de asistencias durante la importación
- [x] Manejo de errores y reportes de importación

### Frontend
- [x] Desarrollar página de importación de asistencias
- [x] Implementar preview de datos antes de importar
- [x] Mostrar errores y advertencias de validación
- [x] Agregar confirmación antes de guardar

### Testing
- [x] Escribir tests para importación de asistencias
- [x] Crear checkpoint final con importación de asistencias


## Sistema de Calendario Académico - Fase 4

### Backend
- [x] Actualizar esquema de base de datos con tabla de eventos académicos
- [x] Implementar helpers para gestión de eventos académicos
- [x] Crear procedimientos tRPC para CRUD de eventos
- [x] Actualizar cálculo de ausentismo para excluir fechas especiales
- [x] Validar que las fechas de eventos no se solapen

### Frontend
- [x] Desarrollar página de calendario académico con vista mensual
- [x] Implementar formulario para crear eventos académicos
- [x] Agregar edición y eliminación de eventos
- [x] Mostrar diferentes tipos de eventos con colores distintos
- [x] Integrar calendario en Dashboard para vista rápida

### Testing
- [x] Escribir tests para gestión de eventos académicos
- [x] Escribir tests para exclusión de fechas en cálculo de ausentismo
- [x] Crear checkpoint final con calendario académico


## Sistema de Carga Múltiple de Formatos - Fase 5

### Backend
- [ ] Instalar dependencias para parsear Word y PDF
- [ ] Crear utilidad para parsear archivos Word (.docx)
- [ ] Crear utilidad para parsear archivos PDF
- [ ] Actualizar importador de estudiantes para soportar múltiples formatos
- [ ] Actualizar importador de asistencias para soportar múltiples formatos
- [ ] Detectar automáticamente el formato del archivo

### Frontend
- [ ] Actualizar interfaz de carga de datos para aceptar múltiples formatos
- [ ] Mostrar vista previa de datos parseados de cualquier formato
- [ ] Agregar indicador visual del formato detectado
- [ ] Mejorar validación de datos según el formato

### Testing
- [ ] Escribir tests para parseo de Word
- [ ] Escribir tests para parseo de PDF
- [ ] Escribir tests para detección automática de formato
- [ ] Crear checkpoint final con soporte múltiple de formatos
