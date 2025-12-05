# Política de Privacidad

**Última Actualización:** 20 de noviembre de 2025

**Desarrollado por:** Alexander Urquijo
**Contacto:** cephalopodlabs@gmail.com
**Ubicación:** Panamá

---

## Introducción

Bienvenido a TallyPod ("nosotros", "nuestro" o "la aplicación"). Estamos comprometidos con proteger tu privacidad y manejar tu información personal de manera transparente y segura. Esta Política de Privacidad explica qué datos recopilamos, cómo los usamos y tus derechos respecto a tu información.

Al usar TallyPod, aceptas la recopilación y uso de información como se describe en esta política.

---

## 1. Información que Recopilamos

### 1.1 Información que Proporcionas Directamente

Cuando usas TallyPod, recopilamos:

- **Información de Cuenta:** Dirección de correo electrónico, nombre y foto de perfil (cuando inicias sesión con Google)
- **Registros Financieros:** Montos de gastos, fuentes de ingresos, períodos de pago, categorías, descripciones y fechas
- **Imágenes de Recibos:** Fotos de recibos que subes para escaneo OCR
- **Preferencias:** Símbolo de moneda, idioma, tema (modo claro/oscuro) y configuración de vista
- **Datos de Hogar:** Si usas la función de compartir con hogar, recopilamos nombres de hogares e información de miembros

### 1.2 Información Recopilada Automáticamente

- **Información del Dispositivo:** Tipo de dispositivo, versión del sistema operativo (solo para propósitos de compatibilidad)
- **Datos de Uso:** Funciones de la app que utilizas, para mejorar la experiencia del usuario (sin rastreo ni analíticas)

### 1.3 Información que NO Recopilamos

- **NO** usamos cookies de rastreo
- **NO** usamos servicios de analíticas (sin Google Analytics, sin Firebase Analytics)
- **NO** recopilamos tu ubicación
- **NO** compartimos tus datos con anunciantes
- **NO** vendemos tu información personal a terceros

---

## 2. Cómo Usamos tu Información

Usamos tu información únicamente para los siguientes propósitos:

- **Proporcionar Funcionalidad Principal:** Almacenar y gestionar tus gastos, ingresos y recibos
- **Procesamiento OCR:** Extraer texto de imágenes de recibos usando Google ML Kit en el dispositivo (las imágenes se procesan localmente en tu dispositivo, no se envían a servidores externos)
- **Sincronización en la Nube:** Sincronizar tus datos entre tus dispositivos usando Supabase (almacenamiento seguro en la nube)
- **Autenticación:** Verificar tu identidad usando Google Sign-In
- **Compartir con Hogar:** Si está habilitado, compartir gastos e ingresos con miembros del hogar que invites
- **Soporte al Cliente:** Responder a tus consultas y solicitudes de soporte

**NO** usamos tus datos para marketing, publicidad o cualquier propósito no directamente relacionado con la funcionalidad de la app.

---

## 3. Almacenamiento y Seguridad de Datos

### 3.1 Dónde se Almacenan tus Datos

- **Almacenamiento en la Nube:** Tus datos se almacenan de forma segura en servidores de Supabase (base de datos PostgreSQL con encriptación)
- **Almacenamiento Local:** Algunos datos se almacenan en caché localmente en tu dispositivo para acceso sin conexión (base de datos SQLite encriptada)

### 3.2 Medidas de Seguridad

Implementamos medidas de seguridad estándar de la industria:

- **Encriptación:** Todos los datos transmitidos entre tu dispositivo y nuestros servidores están encriptados usando HTTPS/TLS
- **Autenticación:** Autenticación segura OAuth 2.0 vía Google Sign-In
- **Control de Acceso:** Seguridad a nivel de fila (RLS) asegura que los usuarios solo puedan acceder a sus propios datos
- **Protección Biométrica:** Bloqueo opcional con huella digital/Face ID para seguridad adicional

### 3.3 Retención de Datos

- Tus datos se retienen mientras tu cuenta esté activa
- Puedes eliminar todos tus datos en cualquier momento desde la pantalla de Perfil (opción "Eliminar Todos los Datos")
- Si eliminas tu cuenta, todos tus datos se eliminan permanentemente de nuestros servidores en un plazo de 30 días

---

## 4. Servicios de Terceros

TallyPod usa los siguientes servicios de terceros:

### 4.1 Google Sign-In
- **Propósito:** Autenticación
- **Datos Compartidos:** Correo electrónico, nombre, foto de perfil
- **Política de Privacidad:** [https://policies.google.com/privacy](https://policies.google.com/privacy)

### 4.2 Supabase (Base de Datos en la Nube)
- **Propósito:** Almacenamiento y sincronización de datos
- **Datos Compartidos:** Todos los datos del usuario (gastos, ingresos, preferencias)
- **Política de Privacidad:** [https://supabase.com/privacy](https://supabase.com/privacy)
- **Ubicación:** Los datos se almacenan en servidores en Estados Unidos

### 4.3 Google ML Kit (OCR)
- **Propósito:** Reconocimiento de texto en imágenes de recibos
- **Procesamiento de Datos:** Todo el procesamiento ocurre **en tu dispositivo** (no se envían datos a servidores de Google)
- **Política de Privacidad:** [https://policies.google.com/privacy](https://policies.google.com/privacy)

---

## 5. Compartir Datos

**NO** vendemos, alquilamos ni compartimos tu información personal con terceros, excepto:

- **Miembros del Hogar:** Si usas la función de compartir con hogar, otros miembros que invites pueden ver gastos e ingresos compartidos
- **Obligaciones Legales:** Si es requerido por ley, orden judicial o regulación gubernamental
- **Proveedores de Servicios:** Usamos Supabase y Google Sign-In como se describe arriba (están sujetos a estrictos acuerdos de confidencialidad)

---

## 6. Tus Derechos

Dependiendo de tu ubicación, puedes tener los siguientes derechos:

### 6.1 Derechos Generales (Todos los Usuarios)

- **Acceso:** Ver todos tus datos en la app
- **Corrección:** Editar o actualizar tu información en cualquier momento
- **Eliminación:** Eliminar todos tus datos desde Perfil > Eliminar Todos los Datos
- **Exportación:** Exportar todos los datos de tu cuenta en formato legible por máquina (CSV/TXT) - **GRATIS para todos los usuarios** (cumplimiento GDPR/CCPA). Los usuarios Premium también tienen acceso a reportes de análisis avanzados con gráficos y tendencias.

### 6.2 Derechos GDPR (Usuarios de la UE)

Si estás en la Unión Europea, tienes derechos adicionales:

- **Derecho al Olvido:** Solicitar eliminación completa de tus datos (contáctanos en cephalopodlabs@gmail.com)
- **Portabilidad de Datos:** Exportar tus datos en formato legible por máquina (CSV)
- **Objeción:** Objetar el procesamiento de datos (puedes dejar de usar la app y eliminar tus datos)
- **Restricción:** Solicitar limitación del procesamiento de datos
- **Presentar Queja:** Contactar a tu autoridad local de protección de datos

### 6.3 Derechos CCPA (Usuarios de California)

Si eres residente de California, tienes derecho a:

- Conocer qué información personal recopilamos
- Solicitar eliminación de tu información personal
- Optar por no vender información personal (nosotros NO vendemos tus datos)

### 6.4 Ley 81 de 2019 de Panamá

Como app basada en Panamá, cumplimos con la Ley de Protección de Datos de Panamá:

- Tienes derecho a acceder, rectificar, cancelar y oponerte (derechos ARCO)
- Puedes ejercer estos derechos contactándonos en cephalopodlabs@gmail.com

---

## 7. Privacidad de Menores

TallyPod **no está destinada a menores de 13 años** (o menores de 16 en la UE). No recopilamos intencionalmente información personal de menores. Si descubrimos que un menor nos ha proporcionado información personal, la eliminaremos inmediatamente.

---

## 8. Transferencias Internacionales de Datos

Tus datos pueden ser transferidos y almacenados en servidores ubicados en Estados Unidos (servidores de Supabase). Al usar TallyPod, consientes esta transferencia. Aseguramos que se implementen salvaguardas apropiadas para proteger tus datos.

---

## 9. Cambios a esta Política de Privacidad

Podemos actualizar esta Política de Privacidad de vez en cuando. Cuando lo hagamos:

- Actualizaremos la fecha de "Última Actualización" en la parte superior
- Te notificaremos por correo electrónico o notificación en la app
- El uso continuado de la app después de los cambios constituye aceptación

---

## 10. Contáctanos

Si tienes preguntas, inquietudes o solicitudes respecto a tu privacidad o esta política, por favor contáctanos:

**Email:** cephalopodlabs@gmail.com
**Desarrollador:** Alexander Urquijo
**Tiempo de Respuesta:** Buscamos responder en un plazo de 48 horas

---

## 11. Eliminación de Cuenta

### 11.1 Cómo Eliminar tu Cuenta

Puedes eliminar permanentemente tu cuenta de TallyPod y todos los datos asociados en cualquier momento. Hay dos formas de hacerlo:

**Método 1: Eliminar desde la App (Recomendado)**

1. Abre TallyPod y ve a **Perfil** (navegación inferior)
2. Desplázate hacia abajo hasta la sección **Gestión de Cuenta**
3. Toca **"Eliminar Todos los Datos"**
4. Lee el mensaje de advertencia cuidadosamente (esta acción es irreversible)
5. Confirma la eliminación
6. Se cerrará tu sesión automáticamente

**Método 2: Solicitar Eliminación por Email**

Si no puedes acceder a la app o prefieres solicitar la eliminación por email:

- Envía un correo a cephalopodlabs@gmail.com
- Asunto: "Solicitud de Eliminación de Cuenta"
- Incluye: Tu dirección de correo registrada y motivo (opcional)
- Procesaremos tu solicitud en un plazo de **48 horas**

### 11.2 Qué Datos se Eliminan

Cuando eliminas tu cuenta, los siguientes datos se eliminan permanentemente:

- **Inmediatamente de tu dispositivo:**
  - Todos los registros de gastos (recibos, montos, categorías, descripciones)
  - Todas las fuentes de ingresos y períodos de pago
  - Todas las imágenes de recibos almacenadas localmente
  - Preferencias de usuario (tema, idioma, modo de vista)
  - Membresías e invitaciones de hogares
  - Base de datos SQLite local (completamente eliminada)

- **En un plazo de 30 días de los servidores en la nube:**
  - Todos los datos almacenados en Supabase (base de datos PostgreSQL)
  - Información de cuenta de usuario (correo, nombre, foto de perfil)
  - Todos los datos del hogar si eres el propietario

- **Retenidos por cumplimiento legal (90 días máximo):**
  - Registros de transacciones (si aplica para suscripciones premium)
  - Registros de pagos (requeridos por regulaciones fiscales y financieras)
  - Estos se anonimizan y no pueden vincularse de vuelta a ti

### 11.3 Advertencias Importantes

**⚠️ La eliminación de cuenta es permanente e irreversible.** Una vez eliminada:

- **No puedes recuperar** tus gastos, ingresos o recibos
- Si eres propietario de un hogar, **todos los miembros perderán acceso** a los datos compartidos
- Necesitarás **crear una nueva cuenta** si quieres usar TallyPod nuevamente
- **No podemos restaurar** datos eliminados, incluso si nos contactas inmediatamente después de la eliminación

### 11.4 Alternativa: Exporta tus Datos Antes de Eliminar

**Recomendamos encarecidamente exportar todos los datos de tu cuenta** antes de eliminarla (esto es GRATIS para todos los usuarios):

1. Ve a **Perfil** (navegación inferior)
2. Desplázate a la sección **Gestión de Cuenta**
3. Toca **"Exportar Datos de Cuenta"**
4. Se generará un archivo ZIP con todos tus datos (gastos, ingresos, hogares, configuraciones)
5. Comparte o guarda el archivo en tu dispositivo o almacenamiento en la nube
6. Luego procede con la eliminación de cuenta si lo deseas

*Nota: Esta exportación básica cumple con el Artículo 20 del GDPR y el § 1798.100 de CCPA (Derecho a la Portabilidad de Datos). Los usuarios Premium también pueden generar reportes de análisis avanzados.*

---

## 12. Cumplimiento Legal

Esta Política de Privacidad cumple con:

- **GDPR** (Reglamento General de Protección de Datos - UE)
- **CCPA** (Ley de Privacidad del Consumidor de California - EE.UU.)
- **Ley 81 de 2019** (Ley de Protección de Datos Personales de Panamá)
- **Políticas para Desarrolladores de Google Play Store**
- **Directrices de Apple App Store**

---

**Gracias por confiar en TallyPod con tus datos financieros. Tu privacidad nos importa.**
