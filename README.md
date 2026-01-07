# OdontoApp — Análisis Facial Ortodóntico

![DentiStudio](https://img.shields.io/badge/Clínica-DentiStudio-4e73df?logo=github)
![Versión](https://img.shields.io/badge/v2.1-Estable-1cc88a)

Sistema profesional de análisis facial cuantitativo con inteligencia artificial, diseñado para **DentiStudio** y listo para integrarse en **OdontoApp**.

✅ **100% web** — sin instalación, funciona offline tras carga inicial  
✅ Sin distorsión de imágenes — preserva proporciones originales  
✅ Detalle médico validado: tercios, ángulos, Línea E, simetría  
✅ Soporte de IA (`face-api.js`) + edición manual precisa  

---

## 🚀 Características

| Módulo | Funcionalidad |
|-------|----------------|
| 📸 **Carga de imágenes** | Drag & drop + click. Mantiene proporción (contain). |
| 🤖 **Detección IA** | Puntos faciales automáticos (frontal real, perfil simulado). |
| 📏 **Mediciones** | Tercios faciales, ángulos nasolabial/mentolabial, convexidad, etc. |
| 📊 **Diagnóstico** | Indicadores de estado (normal/límite/alterado). |
| 💾 **Exportación** | JSON estructurado listo para historial clínico. |

---

## 🖼️ Capturas de Pantalla

*(Al abrir `index.html`, toma capturas y añádelas aquí. Ejemplo:)*

![Vista frontal con landmarks](docs/screenshot-front.png)
> _Detección de puntos en vista frontal con coordenadas y listado interactivo._

![Reporte JSON](docs/screenshot-json.png)
> _Exportación en JSON con metadatos clínicos compatibles con sistemas EHR._

---

## 🛠️ Cómo Usar

1. Clona o descarga este repositorio  
2. Abre `index.html` en cualquier navegador moderno (Chrome, Edge, Firefox)  
3. Carga fotos del paciente (frontal y perfil)  
4. Detecta puntos con IA o añádelos manualmente  
5. Analiza resultados y exporta a JSON  

> 🔒 **Privacidad**: Todo ocurre **en tu navegador**. No se suben imágenes a servidores.

---

## 📦 Próximas Mejoras (Roadmap)

| Etapa | Funcionalidad |
|------|----------------|
| v2.2 | Soporte móvil táctil (zoom + arrastre en canvas) |
| v2.3 | Integración `jsPDF` para reporte PDF profesional |
| v3.0 | Modelo de IA entrenado para perfil + sonrisa |
| v3.1 | API REST para integración con OdontoApp |

---

## 📬 Soporte

Para clínicas asociadas a **DentiStudio**, contáctanos:  
✉️ `soporte@denti.studio`  
🌐 [https://denti.studio](https://denti.studio)

*Desarrollado con ❤️ para la odontología peruana.*
