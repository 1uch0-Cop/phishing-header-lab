# Phishing Header Lab

Laboratorio educativo para el análisis defensivo de cabeceras de correo electrónico.

La herramienta examina indicadores básicos relacionados con:

- coherencia entre `From`, `Return-Path`, `Reply-To` y `Message-ID`;
- resultados de autenticación SPF, DKIM y DMARC;
- alineación entre dominios;
- clasificación orientativa del riesgo;
- escenarios de phishing y Business Email Compromise (BEC).

## Propósito

Este proyecto está diseñado para actividades educativas de ciberseguridad, talleres formativos, cursos técnicos y ejercicios introductorios de blue team.

No reemplaza el análisis realizado por especialistas ni constituye una herramienta automática de respuesta a incidentes.

## Privacidad

El análisis se realiza localmente en el navegador. La aplicación no incorpora backend, telemetría, almacenamiento remoto ni código para transmitir las cabeceras ingresadas.

Antes de utilizar una cabecera real, deben anonimizarse:

- nombres de personas;
- direcciones de correo;
- direcciones IP;
- dominios internos;
- identificadores de mensajes;
- nombres de servidores;
- cualquier otro dato personal o institucional.

No se recomienda publicar cabeceras reales en capturas, repositorios, issues o materiales compartidos.

## Funcionalidades

- Análisis de SPF, DKIM y DMARC.
- Comparación de dominios entre campos relevantes.
- Clasificación de riesgo bajo, moderado o alto.
- Explicación educativa de cada hallazgo.
- Ejemplos ficticios de correo legítimo, phishing y BEC.
- Procesamiento completamente local.
- Interfaz adaptable y compatible con modo oscuro.
- Renderizado seguro de datos mediante nodos del DOM.

## Ejemplos seguros

Los ejemplos incluidos utilizan exclusivamente:

- dominios reservados como `.example` y `.invalid`;
- direcciones IP reservadas para documentación;
- organizaciones, personas y servicios ficticios.

No representan incidentes, empresas ni infraestructuras reales.

## Uso local

Clona el repositorio:

```bash
git clone https://github.com/1uch0-Cop/phishing-header-lab.git
cd phishing-header-lab
```

Abre el archivo principal:

```bash
xdg-open index.html
```

También puede abrirse manualmente desde cualquier navegador moderno.

## Uso educativo sugerido

1. Seleccionar uno de los ejemplos ficticios.
2. Revisar los campos principales de la cabecera.
3. Analizar SPF, DKIM y DMARC.
4. Comparar los dominios identificados.
5. Formular una conclusión manual.
6. Contrastar la conclusión con el resultado de la herramienta.
7. Fundamentar si el caso corresponde a un correo legítimo, phishing o BEC.

## Resultados de aprendizaje

- Interpretar cabeceras básicas de correo.
- Comprender SPF, DKIM y DMARC.
- Reconocer discrepancias entre dominios.
- Identificar señales iniciales de spoofing y BEC.
- Aplicar criterios de privacidad al trabajar con evidencias.
- Desarrollar pensamiento crítico en análisis defensivo.

## Tecnologías

- HTML5
- CSS3
- JavaScript
- Sin frameworks
- Sin dependencias externas
- Sin backend

## Limitaciones

La puntuación generada es orientativa.

Un resultado bajo no garantiza que un mensaje sea legítimo, porque también deben analizarse:

- contenido y contexto;
- enlaces;
- archivos adjuntos;
- reputación de dominios e IP;
- cadena completa de campos `Received`;
- alineación real de SPF y DKIM;
- comportamiento solicitado al destinatario.

## Publicación con GitHub Pages

Desde la configuración del repositorio:

1. Abrir `Settings`.
2. Seleccionar `Pages`.
3. Elegir la rama `main`.
4. Seleccionar la carpeta `/root`.
5. Guardar la configuración.

## Uso responsable

Este proyecto tiene una finalidad educativa y defensiva. No debe utilizarse para suplantación, fraude, acceso no autorizado ni tratamiento indebido de información personal.

## Licencia

Copyright (C) 2026 1uch0-Cop

Este proyecto se distribuye bajo la licencia GNU Affero General Public License, versión 3 o cualquier versión posterior: `AGPL-3.0-or-later`.

Consulte el archivo [LICENSE](LICENSE).
