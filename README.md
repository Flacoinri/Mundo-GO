# Mundo GO: Grilla Digital de Canales 📺

**Aplicación Web Inclusiva y Responsiva para Búsqueda de Canales**

Mundo GO es una solución web ligera diseñada para digitalizar y simplificar la grilla de canales de Mundo Telecomunicaciones. El proyecto nace con un fuerte enfoque social y de accesibilidad: **ayudar a las personas de la tercera edad** a encontrar sus canales favoritos de forma rápida, evitando la frustración de buscar manualmente en el decodificador tradicional.

---

## 🛠️ Stack Tecnológico

Al ser un proyecto enfocado en velocidad y portabilidad, se desarrolló como una aplicación "Zero-Dependencies" (sin necesidad de servidores complejos):
* **Estructura:** HTML5 semántico.
* **Estilos:** CSS3 potenciado por **Tailwind CSS** (vía CDN) para un diseño 100% responsivo.
* **Lógica:** **Vanilla JavaScript** (ES6+) para manipulación del DOM y filtrado en tiempo real.
* **Tipografía:** Google Fonts (Montserrat) para máxima legibilidad.

---

## ✨ Características Principales

### 🔍 Motor de Búsqueda en Tiempo Real
Buscador optimizado que filtra los resultados instantáneamente (keyup) ya sea ingresando el **nombre del canal** (ej: *Mega*) o directamente su **número** (ej: *246*).

### 🏷️ Filtrado por Categorías
Navegación intuitiva mediante "píldoras" (badges) deslizables que agrupan los más de 260 canales en categorías lógicas:
* Nacionales e Infantiles.
* Cine, Series y Variedades.
* Deportes y Noticias.
* Canales Regionales (amplia cobertura).

### 📱 Diseño UI/UX Accesible
* **Mobile-First:** La grilla (`CSS Grid`) se adapta automáticamente desde 2 columnas en teléfonos móviles hasta 6 columnas en pantallas de escritorio.
* **Alto Contraste:** Uso de los colores corporativos de la marca (Azul y Cyan) contrastados con fondos claros y tarjetas limpias para facilitar la lectura a usuarios con visión reducida.
* **Feedback Visual:** Animaciones suaves en hover y un estado visual de "Canal no encontrado" (Empty State).

---

## 🚀 Uso y Despliegue

Este proyecto es de tipo **Plug & Play**. No requiere Node.js, bases de datos, ni procesos de compilación.

1. Clona este repositorio:
   ```bash
   git clone [https://github.com/Flacoinri/Mundo-GO.git](https://github.com/Flacoinri/Mundo-GO.git)
