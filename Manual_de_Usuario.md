# Manual de Usuario - Sistema de Tutoría UPT

Este documento describe cómo utilizar las dos aplicaciones que componen el sistema de tutoría: el formulario web para estudiantes y la aplicación móvil para asesores.

---

## 1. Aplicación Web para Estudiantes y Externos

Esta aplicación está diseñada para que los estudiantes de la UPT o personas externas puedan registrar una solicitud de atención de tutoría de forma rápida.

### 1.1. Acceso a la Aplicación

1.  Abre cualquier navegador web (Chrome, Edge, Firefox, etc.).
2.  Ingresa a la siguiente URL proporcionada por la administración:
    *   **URL:** `https://[id-del-proyecto].web.app` *(Nota: Reemplazar con la URL real de Firebase Hosting)*.

### 1.2. Registro de una Nueva Atención

Al ingresar a la página, verás el formulario "Registro de Atención - Tutoría UPT". Sigue estos pasos para registrar tu solicitud:

1.  **Tipo de Usuario:**
    *   Selecciona **"Estudiante"** si eres un alumno matriculado en la UPT.
    *   Selecciona **"Externo"** si no eres estudiante de la UPT.

2.  **Nombres y Apellidos:**
    *   Completa tus nombres y apellidos en los campos correspondientes.

3.  **Identificación:**
    *   Si seleccionaste "Estudiante", se te pedirá tu **Código de Estudiante**.
    *   Si seleccionaste "Externo", se te pedirá tu **DNI** (8 dígitos).

4.  **Tipo de Atención:**
    *   Despliega la lista y selecciona el motivo de tu consulta (ej. "Motivo personal", "Reforzamiento", etc.).

5.  **Enviar Formulario:**
    *   Haz clic en el botón **"Registrar Atención"**.
    *   Si el registro es exitoso, verás un mensaje de confirmación y los campos del formulario se limpiarán, dejándolo listo para un nuevo registro.
    *   Si ocurre un error, se mostrará un mensaje indicando el problema.

---

## 2. Aplicación Móvil para Asesores (Android)

Esta aplicación permite a los tutores y administradores gestionar las atenciones registradas por los estudiantes.

### 2.1. Instalación

1.  Recibirás un archivo de instalación con el nombre `app-debug.apk` (o similar).
2.  Transfiere este archivo a tu dispositivo Android e instálalo. (Es posible que necesites habilitar la instalación desde fuentes desconocidas en la configuración de tu teléfono).

### 2.2. Inicio de Sesión

1.  Abre la aplicación "Portal de Asesores".
2.  Verás una pantalla de inicio de sesión.
3.  **Correo Electrónico:** Ingresa el correo de asesor que te fue asignado por el administrador.
4.  **Contraseña:** Ingresa la contraseña correspondiente.
5.  Haz clic en el botón **"Iniciar Sesión"**.

*Nota: Si las credenciales son incorrectas o tu cuenta está deshabilitada, la aplicación te mostrará un mensaje de error.*

### 2.3. Dashboard de Atenciones

Una vez que inicies sesión, accederás al "Dashboard de Atenciones", que es la pantalla principal. Aquí puedes:

1.  **Ver Estadísticas:**
    *   En la parte superior, una tarjeta muestra un gráfico circular con un resumen estadístico de los tipos de atención más comunes. También verás el número total de atenciones registradas.

2.  **Consultar Atenciones Recientes:**
    *   Debajo de las estadísticas, encontrarás una lista con las últimas atenciones registradas por los estudiantes.
    *   Cada tarjeta de atención muestra:
        *   El nombre del estudiante ("Pepe Pilco" en el ejemplo).
        *   El tipo de atención solicitado.
        *   La fecha y hora del registro.

3.  **Filtrar Atenciones (Próximamente):**
    *   El ícono de filtro (▼) en la tarjeta de estadísticas permitirá en futuras versiones filtrar las atenciones por tipo, fecha, etc.

4.  **Registrar una Nueva Atención (Manual):**
    *   El botón flotante verde con el símbolo `+` te permitirá añadir una nueva atención manualmente, en caso de que un estudiante lo solicite de forma presencial.

5.  **Generar Reportes (Próximamente):**
    *   El botón flotante azul oscuro permitirá en futuras versiones exportar las atenciones a un archivo PDF o Excel.

### 2.4. Cerrar Sesión

1.  Para salir de tu cuenta, haz clic en el ícono de "salir" (una puerta con una flecha) ubicado en la esquina superior derecha del dashboard.
