# R&R NEXUS — prototipo interactivo

**R&R NEXUS** es el concepto de plataforma de R&R Business & Fitness Consulting para unificar CRM comercial, proyectos de consultoría y portal de clientes.

## Contenido de esta primera versión
- Dashboard con métricas resumen.
- CRM de oportunidades: alta, búsqueda y cambio de fase.
- Proyectos: creación, seguimiento de avance y fechas.
- Clientes: registro y vista previa de su portal.
- Tareas y entregables.
- Vista de portal de cliente de demostración.
- Exportación de los datos demo en JSON.
- Diseño responsive con identidad oscura y acento turquesa `#00D7B7`.

## Abrir
Abrir `rr-nexus/index.html` en un navegador. Los registros se guardan en el almacenamiento local de ese navegador.

## Limitaciones importantes
Esta es una **demo de interfaz**, no una aplicación multiusuario lista para clientes. No tiene autenticación real, backend, base de datos compartida, autorización por cliente ni almacenamiento seguro. La opción de vista de cliente es solo una previsualización y no debe usarse para compartir datos reales o confidenciales.

## Siguiente etapa para producción
1. Crear un repositorio independiente `rr-nexus` (este prototipo se encuentra aislado en la rama `rr-nexus-prototype` del repositorio actual para no tocar `main`).
2. Implementar autenticación real y roles (administrador R&R, consultor y cliente).
3. Usar una base de datos con políticas de acceso por tenant/cliente (por ejemplo Supabase con Row Level Security).
4. Guardar documentos en almacenamiento privado con permisos por proyecto.
5. Añadir invitaciones de usuarios, recuperación de contraseña, auditoría de cambios y reglas de privacidad.
6. Conectar el dominio y desplegar el frontend.
7. Validar RGPD, textos legales, copias de seguridad y gestión de consentimiento antes de introducir datos personales reales.

## Identidad
- Producto: **R&R NEXUS**
- Descriptor: **Business Platform**
- Promesa: CRM + proyectos + portal de cliente en un mismo espacio.
- Colores: negro/verde petróleo, blanco y turquesa eléctrico `#00D7B7`.

Los datos de muestra son ficticios y solo ilustran el flujo de la interfaz.
