# 🏛️ Sistema de Registro de Miembros - Iglesia

Un sistema web completo y profesional para el registro de miembros de iglesia, diseñado con formularios específicos por grupos de edad y integración directa con WhatsApp.

## 📋 Descripción

Este sistema permite a los miembros y visitantes de la iglesia registrarse de manera organizada según su grupo de edad, facilitando la gestión pastoral y el seguimiento de la congregación.

## ✨ Características Principales

### 🎯 **Formularios Especializados por Edad**
- **Niños (0-12 años)**: Formulario con información de padres/tutores
- **Jóvenes (13-17 años)**: Enfoque en educación y ministerios juveniles  
- **Adultos (18+ años)**: Información completa personal, familiar y ministerial

### 📱 **Integración con WhatsApp**
- Envío automático de registros al número +503 79468807
- Mensajes formateados y organizados por secciones
- Validación de campos obligatorios antes del envío

### 🔧 **Funciones Avanzadas**
- Cálculo automático de edad basado en fecha de nacimiento
- Validación de rangos de edad por formulario
- Campos dinámicos que se muestran/ocultan según selecciones
- Limpieza automática de formularios después del envío
- Diseño responsive para móviles y tablets

## 🗂️ Estructura del Proyecto

```
formulario/
├── index.html                 # Página principal con selección de formularios
├── formulario-ninos.html      # Formulario para niños (0-12 años)
├── formulario-jovenes.html    # Formulario para jóvenes (13-17 años)
├── formulario-adultos.html    # Formulario para adultos (18+ años)
├── test-adultos.html          # Página de pruebas para formulario de adultos
├── logo/
│   └── central.png           # Logo de la iglesia
└── README.md                 # Este archivo
```

## 🚀 Instalación y Uso

### Requisitos
- Servidor web (Apache, Nginx, o servidor local)
- Navegador web moderno
- Conexión a internet (para WhatsApp)

### Instalación
1. Descarga o clona todos los archivos en tu servidor web
2. Asegúrate de que el logo esté en la carpeta `logo/central.png`
3. Abre `index.html` en tu navegador

### Configuración
- **Número de WhatsApp**: Configurado para +503 79468807
- **Iglesias disponibles**: Central, La Tekera, El Pital, El Sauce
- **Validaciones de edad**: Automáticas por formulario

## 📊 Detalles de los Formularios

### 🧸 **Formulario de Niños (0-12 años)**
**Información requerida:**
- Datos del niño (nombre, edad, fecha nacimiento)
- Información de padres/tutores
- Contacto de emergencia
- Información médica básica
- Iglesia de asistencia

**Características especiales:**
- Enfoque en información de padres
- Campos médicos simplificados
- Validación de edad máxima 12 años

### 🎓 **Formulario de Jóvenes (13-17 años)**
**Información requerida:**
- Datos personales con cálculo automático de edad
- Información familiar (padres y emergencia)
- Educación actual
- Participación en ministerios
- Información médica

**Características especiales:**
- Ministerios juveniles específicos
- Información educativa
- Validación de rango 13-17 años

### 👥 **Formulario de Adultos (18+ años)**
**Información requerida:**
- Información personal completa (incluye DUI, estado civil)
- Información familiar (cónyuge, hijos)
- Información laboral y educativa
- Experiencia cristiana y ministerial
- Información médica detallada

**Características especiales:**
- Campos dinámicos para cónyuge e hijos
- Ministerios variados disponibles
- Email opcional
- Información médica completa (medicamentos, alergias)

## 🎨 Diseño y Tecnologías

### **Frontend**
- **HTML5**: Estructura semántica y accesible
- **CSS3**: Diseño moderno con gradientes y efectos
- **JavaScript**: Validaciones y funcionalidades dinámicas
- **Responsive Design**: Compatible con móviles y tablets

### **Características de Diseño**
- Gradientes de colores distintivos por formulario
- Iconos intuitivos para cada sección
- Animaciones suaves y efectos visuales
- Diseño card-based para mejor organización

## 📱 Integración con WhatsApp

### **Configuración del Mensaje**
Los mensajes se envían estructurados en secciones:

```
*REGISTRO DE [TIPO] - IGLESIA*

*👤 INFORMACIÓN PERSONAL:*
*👨‍👩‍👧‍👦 INFORMACIÓN FAMILIAR:*
*💼 INFORMACIÓN LABORAL:*
*✝️ EXPERIENCIA CRISTIANA:*
*🙏 MINISTERIOS Y SERVICIO:*
*🚨 CONTACTO DE EMERGENCIA:*
*🏥 INFORMACIÓN MÉDICA:*

*Registro completado exitosamente*
```

### **Número de Destino**
- **WhatsApp**: +503 79468807
- **País**: El Salvador

## ⚙️ Funciones JavaScript

### **Validaciones Automáticas**
- Cálculo preciso de edad considerando año, mes y día
- Validación de rangos de edad específicos por formulario
- Verificación de campos obligatorios antes de envío

### **Funciones Dinámicas**
- Mostrar/ocultar secciones según selecciones
- Habilitar/deshabilitar campos relacionados
- Limpieza automática post-envío

### **Integración WhatsApp**
- Formateo automático de mensajes
- Codificación URL para caracteres especiales
- Apertura de WhatsApp Web en nueva ventana

## 🏛️ Configuración de Iglesias

El sistema está configurado para las siguientes iglesias:
- **Iglesia Central** (principal)
- **Filial La Tekera**
- **Filial El Pital** 
- **Filial El Sauce**

## 🔒 Seguridad y Privacidad

- **Sin almacenamiento local**: Los datos se envían directamente por WhatsApp
- **Validación del lado cliente**: Previene envío de datos incompletos
- **Campos opcionales claramente marcados**: Respeta la privacidad del usuario
- **No requiere registro**: Sistema anónimo y directo

## 🧪 Testing

### **Página de Pruebas**
- Archivo `test-adultos.html` incluido para pruebas sistemáticas
- Lista de verificación de todas las funciones
- Guía de campos obligatorios

### **Pruebas Recomendadas**
1. **Cálculo de edad**: Probar con diferentes fechas
2. **Validaciones**: Intentar enviar con campos vacíos
3. **WhatsApp**: Verificar formato de mensaje
4. **Responsividad**: Probar en diferentes dispositivos
5. **Campos dinámicos**: Verificar show/hide de secciones

## 📞 Soporte

Para modificaciones o soporte técnico:
- Revisar el código JavaScript para validaciones
- Modificar números de WhatsApp en las funciones correspondientes
- Ajustar iglesias en los elementos `<select>`
- Personalizar estilos CSS según necesidades

## 📈 Estadísticas del Proyecto

- **Total de archivos**: 6 archivos HTML + 1 imagen
- **Líneas de código**: ~2000+ líneas
- **Campos de formulario**: 50+ campos únicos
- **Validaciones JavaScript**: 15+ funciones
- **Compatibilidad**: IE11+, Chrome, Firefox, Safari, Edge

## 📝 Changelog

### Versión 1.0 (Agosto 2025)
- ✅ Sistema completo de 3 formularios
- ✅ Integración WhatsApp funcionando
- ✅ Cálculo automático de edad
- ✅ Validaciones completas
- ✅ Diseño responsive
- ✅ Limpieza automática de formularios

---

## 📖 Licencia

Este proyecto está diseñado específicamente para uso eclesiástico. Libre para uso y modificación según las necesidades de cada congregación.

**Desarrollado con ❤️ para la comunidad de fe**
