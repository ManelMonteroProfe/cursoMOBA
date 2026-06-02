# PRD-PELUQUERIA.MD

## 1. Introducción y Objetivos
Este documento define los requisitos para el desarrollo de la página web de **Peluquería Manel**. El objetivo principal es crear una presencia digital atractiva, moderna y funcional que convierta las visitas en citas físicas en la peluquería, automatizando el proceso de reserva.

## 2. Público Objetivo (User Persona)
* **Perfil:** Chicas jóvenes de entre 18 y 30 años.
* **Comportamiento:** Usuarias intensivas de *smartphones* y redes sociales (Instagram, TikTok). Valoran la estética visual, las tendencias, la inmediatez y la facilidad para gestionar sus citas online sin necesidad de realizar llamadas telefónicas.

## 3. Arquitectura de la Web (Estructura de Páginas)
La web se estructurará en formato *One-Page* (una sola página fluida con secciones bien definidas) o un sitio web básico de 3 secciones para maximizar la velocidad de carga y la retención:

* **Inicio (Hero):** Imagen de impacto, propuesta de valor clara ("Tu estilo, tus reglas") y botón gigante de reserva.
* **Servicios y Tarifas:** Listado limpio y transparente de servicios (cortes, color, tratamientos, etc.) adaptado a las tendencias del público joven.
* **Sobre Nosotros / El Salón:** Breve texto que conecte con el público y fotos del local (estética *Aesthetic* / Instagrammable).
* **Contacto y Horarios:** Dirección física, mapa de Google Maps, horario de apertura y enlaces a redes sociales.

## 4. Requisitos Funcionales

### RF-01: Sistema de Reservas Online (Integración Crucial)
* La web debe integrar un widget o botón flotante enlazado a **Calendly**.
* Las usuarias deben poder seleccionar el servicio, el día y la hora disponible sin salir de la web (o mediante redirección limpia).
* Confirmación automática de la cita y recordatorio por correo electrónico (gestionado por Calendly).

### RF-02: Enfoque "Mobile-First"
* El 90% del tráfico provendrá de dispositivos móviles. La web debe estar perfectamente optimizada para pantallas pequeñas, con botones fáciles de pulsar con el pulgar.

### RF-03: Conectividad Social
* Botón directo a WhatsApp para dudas rápidas.
* Enlaces destacados a las redes sociales de la peluquería (especialmente Instagram para mostrar el porfolio de trabajos).

## 5. Requisitos No Funcionales

### RNF-01: Rendimiento y Velocidad
* La web debe cargar en menos de 2 segundos en redes 4G/5G. Las imágenes de los trabajos deben estar optimizadas en formato de última generación (WebP).

### RNF-02: Diseño y Estética
* Aplicación estricta de la `GUIA-ESTILO.MD` (tonos azules pastel, tipografías modernas, bordes suaves). El diseño debe transmitir un aire fresco, juvenil y de tendencia.

### RNF-03: SEO Local
* Optimización básica para SEO Local, facilitando que Google indexe la peluquería en su zona geográfica.
