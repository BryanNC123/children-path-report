# **Chapter IV: Product Design**
## **4.1. Style Guidelines**
### 4.1.1. General Style Guidelines

#### Color Palette

### 4.1.2. Web Style Guidelines

## **4.2. Information Architecture**
### 4.2.1. Organization Systems

Children Path combina diferentes sistemas y esquemas de organización de acuerdo con el tipo de contenido, las tareas operativas y el nivel de atención que puede dedicar cada usuario. No se utiliza un único esquema para toda la plataforma, sino que se selecciona la estructura visual (jerárquica, secuencial o matricial) y el esquema de categorización (según audiencia, cronológico, por tópicos o alfabético) que garantice la menor distracción para los conductores y la máxima claridad para las familias y empresas.

| Producto / contenido | Sistema de organización | Aplicación |
| :--- | :--- | :--- |
| **Landing Page** | Jerárquico | El visitante visualiza primero la propuesta de valor centrada en la seguridad y tranquilidad escolar, seguida de los beneficios específicos por segmento, testimonios y llamadas a la acción (CTA) para conductores, colegios y padres. |
| **Flujo de Ejecución de Ruta (Driver App)** | Secuencial | Organiza el recorrido diario paso a paso en su orden natural: inicio de turno, parada secuencial actual, confirmación de abordaje o ausencia, siguiente parada y llegada a la institución educativa. |
| **Plataforma Integral (Web / Móvil)** | Según audiencia | Segmenta el acceso y la arquitectura de información en tres perfiles independientes: interfaz táctil simplificada para Conductores, panel administrativo de monitoreo para Empresas, y aplicación pasiva de seguimiento para Padres de Familia. |
| **Supervisión Parental (Parent Dashboard)** | Jerárquico | El estado actual del estudiante ("En camino", "Abordado", "Llegó al colegio") ocupa el nivel superior de prioridad, seguido por el mapa con seguimiento GPS en tiempo real y, en un nivel complementario, la información del vehículo y la hora estimada de llegada (ETA). |
| **Registro Rápido de Incidencias** | Secuencial y por tópicos | Proceso guiado de dos pasos: el conductor elige el tipo de evento categorizado por temática (Retraso, Desvío, Avería, Emergencia médica) y el sistema completa automáticamente las coordenadas geográficas y la hora. |
| **Trip Timeline y Notificaciones** | Cronológico | Los eventos de abordaje, alertas de proximidad, descensos e incidentes del trayecto se muestran en una línea de tiempo ordenados según el momento exacto en que ocurrieron, desde el más reciente al más antiguo. |
| **Monitoreo de Flota (Company Dashboard)** | Jerárquico | Prioriza en el plano superior el mapa general con alertas activas de desvío y unidades en tránsito, permitiendo descender al detalle por vehículo, conductor asignado y lista de paradas. |
| **Consolidado de Asistencia y Cobranza** | Matricial y alfabético | Cruza en una tabla bidimensional a los estudiantes (ordenados alfabéticamente por apellidos) con los días del mes y su estado de abordaje (Presente, Ausente justificado, Ausente injustificado) para facilitar la facturación mensual.

### 4.2.2. Labeling Systems

En Children Path, el sistema de etiquetado define la manera en que se representan los datos, funcionalidades y accesos dentro de la plataforma. Se utiliza el menor número posible de palabras por etiqueta para simplificar la interfaz, evitar confusiones operativas y minimizar la carga cognitiva del conductor mientras opera el vehículo, así como para brindar claridad inmediata a padres y administradores.

A continuación, se especifican las etiquetas seleccionadas para representar los conjuntos de información de la plataforma y sus respectivas asociaciones:

| Etiqueta | Conjunto de información representado | Asociación y contexto en Children Path |
| :--- | :--- | :--- |
| **Inicio** | Pantalla principal pública | Acceso a la Landing Page con la propuesta de valor y visión general del servicio. |
| **Beneficios** | Ventajas competitivas del producto | Información dirigida a conductores, colegios y familias sobre reducción de tiempos y seguridad. |
| **Planes** | Modelo de precios y suscripción | Tarifas del servicio SaaS según la cantidad de estudiantes y vehículos registrados. |
| **Ingresar** | Autenticación de usuarios | Formulario de inicio de sesión para conductores, administradores de empresa y padres. |
| **Registro** | Creación de cuentas nuevas | Formulario de alta para nuevos conductores independientes, colegios o padres de familia. |
| **Panel** | Vista general del sistema | Tablero principal con métricas resumidas para empresas o estado de viaje para padres (EP04, EP06). |
| **Flota** | Monitoreo vehicular global | Mapa en tiempo real con todas las unidades activas y conductores de la empresa (US07, US35). |
| **Ruta** | Secuencia de paradas del día | Vista del conductor con el itinerario de recojo, direcciones y tiempos estimados (US03, US19). |
| **Estudiantes** | Directorio de alumnos | Lista de estudiantes asignados al conductor, organizados en general o por cada parada (US12, US13). |
| **Abordó** | Marcado de asistencia positiva | Acción de un toque para registrar la subida del menor al vehículo en su parada (US01, US14). |
| **Ausente** | Marcado de inasistencia | Acción directa para indicar que el estudiante no se presentó, omitiendo la parada (US02, US15). |
| **Alerta** | Notificación de proximidad | Mensaje automático al padre indicando que el vehículo está a 5 minutos o 500 metros (US54). |
| **Incidencia** | Reporte de eventos imprevistos | Registro rápido de contingencias en ruta como tráfico severo, accidentes o fallas mecánicas (US05, US26). |
| **Desvío** | Detección de anomalías en ruta | Aviso visual automático cuando una unidad se aparta más de 500 metros del trayecto programado (US08, US39). |
| **Historial** | Trazabilidad temporal | Registro cronológico de viajes realizados, horarios de llegada e incidencias previas (US09, US32, US41). |
| **Asistencia** | Consolidado mensual | Reporte exportable en formato digital para la facturación y cobranza del servicio (US10). |
| **Puntualidad** | Indicadores de desempeño | Métricas porcentuales de llegadas a tiempo por parada, tiempos de espera y velocidad (US11, US44, US51). |
| **Sin conexión** | Estado del sistema local | Indicador visual de almacenamiento local y sincronización pendiente de datos ante cortes de red móvil (US17, US25, US34).

### 4.2.3. SEO Tags and Meta Tags

En esta sección se definen las etiquetas de optimización para motores de búsqueda (SEO) y metadatos que estructuran las principales vistas de la plataforma **Children Path**. Estos elementos garantizan una correcta indexación del sitio público, facilitan el posicionamiento orgánico en búsquedas locales y aseguran una experiencia de usuario consistente tanto en el sitio web estático (Landing Page) como en la aplicación web (Web Application).

| Página / Vista | SEO / Meta Tag | Valor asignado | Propósito / Justificación |
| :--- | :--- | :--- | :--- |
| **Landing Page (Inicio)** | `<title>` | Children Path \| Monitoreo y Seguridad en Transporte Escolar en Lima | Título principal orientado a búsqueda orgánica de padres y conductores en Lima. |
| | `description` | Plataforma digital para el seguimiento en tiempo real del transporte escolar en Lima. Alertas automáticas de proximidad, registro digital de asistencia y rutas seguras. | Resumen conciso que aparece en los resultados del motor de búsqueda (SERP). |
| | `keywords` | transporte escolar lima, movilidad escolar segura, rastreo gps escolar, monitoreo escolar tiempo real, children path, alertas de proximidad | Palabras clave alineadas con la problemática del transporte y el mercado local. |
| | `author` | Creatividad | Startup responsable del desarrollo y gestión de la plataforma. |
| | `robots` | index, follow | Instrucción para que los motores de búsqueda indexen y rastreen los enlaces de la landing page. |
| **Landing Page (Planes y Precios)** | `<title>` | Planes de Suscripción \| Children Path | Identificación de la página comercial de tarifas para colegios y conductores. |
| | `description` | Conoce los planes y tarifas de Children Path para conductores independientes y empresas de transporte escolar. Optimiza rutas y automatiza la asistencia. | Explica la oferta de valor económica y el modelo SaaS de la plataforma. |
| | `keywords` | planes transporte escolar, precio software movilidad escolar, suscripcion gps escolar, gestion de flotas escolares lima | Términos orientados a la conversión de conductores y directores de empresas. |
| | `author` | Creatividad | Identificación de la organización creadora. |
| | `robots` | index, follow | Permite la visibilidad e indexación de la oferta comercial. |
| **Web Application (Iniciar Sesión / Registro)** | `<title>` | Acceso al Sistema \| Children Path | Título funcional para la pantalla de autenticación general. |
| | `description` | Inicia sesión en Children Path para gestionar rutas de transporte escolar, visualizar la flota o seguir el recorrido de tus hijos en tiempo real. | Descripción orientada a la acción del usuario registrado. |
| | `keywords` | login children path, iniciar sesion movilidad escolar, acceso portal padres, portal conductores transporte | Búsquedas directas de usuarios que intentan ingresar a su cuenta. |
| | `author` | Creatividad | Identificación del equipo de desarrollo. |
| | `robots` | noindex, nofollow | Evita la indexación pública de formularios de autenticación por motivos de seguridad. |
| **Web Application (Dashboard de Flota - Empresa)** | `<title>` | Panel de Monitoreo de Flota \| Children Path | Identificador claro de la vista operativa de supervisión vehicular (EP04). |
| | `description` | Panel centralizado para empresas de transporte: supervisión de unidades activas, alertas de desvío y reportes de puntualidad en tiempo real. | Describe la vista de control administrativo de flota. |
| | `keywords` | monitoreo flota escolar, control conductores, alertas desvio ruta, reporte asistencia escolar | Metadatos internos de contexto operativo. |
| | `author` | Creatividad | Identificación de la entidad creadora. |
| | `robots` | noindex, nofollow | Protege la privacidad de los datos operativos y rutas de las unidades. |
| **Web Application (Seguimiento Parental - Padres)** | `<title>` | Rastreo en Vivo de la Movilidad \| Children Path | Título enfocado en la tranquilidad y supervisión en tiempo real del menor (EP06). |
| | `description` | Consulta la ubicación exacta del vehículo escolar de tu hijo, estado de abordaje y hora estimada de llegada. | Explica la funcionalidad de acompañamiento digital para padres de familia. |
| | `keywords` | ubicacion transporte escolar, seguimiento en vivo hijo, confirmacion abordaje colegio | Metadatos de contexto para la vista familiar. |
| | `author` | Creatividad | Identificación del equipo técnico. |
| | `robots` | noindex, nofollow | Resguarda de forma estricta la privacidad y ubicación en tiempo real de los estudiantes. |

### 4.2.4. Searching Systems

### 4.2.5. Navigation Systems



## **4.3. Landing Page UI Design**

### 4.3.1. Landing Page Wireframe

### 4.3.2. Landing Page Mockup

#### Análisis del Diseño Final:

#### Especificaciones Técnicas de la Interfaz:

## **4.4. Web Applications UX/UI Design**

### **4.4.1. Web Applications Wireframes**


### **4.4.2. Web Applications Wireflow Diagrams**


### **4.4.2. Web Applications Mock-ups**


### **4.4.3. Web Applications User Flow Diagrams**

## **4.5. Web Applications Prototyping**


### **4.6.1. Design-Level EventStorming**



### **4.6.2. Software Architecture Context Diagram**


### **4.6.3. Software Architecture Container Diagrams**


### **4.6.4. Software Architecture Components Diagrams**


## **4.7. Object-Oriented Design Software**

### **4.7.1. Class Diagrams**

## **4.8. Database Design**


### **4.8.1. Database Diagrams**

