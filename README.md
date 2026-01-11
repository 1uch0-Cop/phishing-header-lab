# Phishing Header Lab

**Phishing Header Lab** es un recurso didáctico para el análisis de cabeceras de correo electrónico en el contexto de ciberseguridad. Permite estimar el riesgo de phishing basándose en:

- Coherencia de remitentes (From / Return-Path / Reply-To)
- Estado de autenticación (SPF / DKIM / DMARC)
- Anomalías de dominio
- Clasificación del nivel de riesgo (Bajo / Moderado / Alto)

Este proyecto está diseñado para ser utilizado en unidades curriculares de ciberseguridad escolar, talleres formativos, cursos técnicos y actividades de blue teaming básico.

---

## Funcionalidad

El laboratorio permite:

- Pegar cabeceras completas de correos reales
- Analizar autenticación y coherencia de dominios
- Obtener un nivel de riesgo
- Ver explicaciones técnicas de cada hallazgo
- Trabajar con ejemplos integrados (legítimo / phishing / BEC)

Todo funciona **100% en el navegador del usuario**, sin enviar datos a servidores.

---

## Ejemplos incluidos

El laboratorio incorpora ejemplos predefinidos para uso docente:

- **Correo legítimo** (proveedor real)
- **Phishing bancario**
- **BEC (Business Email Compromise)**

Estos permiten generar comparación inmediata entre escenarios.

---

## Uso en el aula (sugerencia docente)

Actividad recomendada:

1. Los estudiantes pegan cabeceras reales (o usan ejemplos).
2. El laboratorio analiza y reporta puntuación + motivos.
3. El docente solicita:
   - Clasificación manual del caso
   - Justificación del diagnóstico
   - Identificación de técnicas usadas por el atacante
4. Comparación final con herramientas automáticas y discusión.

Resultados de aprendizaje:

- Identificar spoofing básico
- Interpretar SPF/DKIM/DMARC
- Evaluar coherencia de dominios
- Desarrollar pensamiento crítico en ciberseguridad

---

## Tecnologías utilizadas

- **HTML5** + **CSS3**
- **JavaScript (ES6)**
- No requiere backend
- No requiere frameworks
- No envía datos a internet

---

## Publicación como página web

Este proyecto puede publicarse fácilmente mediante GitHub Pages:

1. Ir a `Settings` → `Pages`
2. Seleccionar:
   - Branch: `main`
   - Folder: `/root`
3. Guardar y esperar la URL generada

---

**Licencia**
Uso educativo abierto. Puede reutilizarse, adaptarse y distribuirse en contextos escolares.
