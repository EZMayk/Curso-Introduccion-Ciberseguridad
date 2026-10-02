# Cuestionario de Introducción a la Ciberseguridad

Cuestionario web en español para estudiar los cinco módulos del curso **Introduction to Cybersecurity** de Cisco Networking Academy. Funciona sin conexión, no requiere instalación y está adaptado para computadoras y celulares.

## Objetivo

El proyecto combina preguntas conceptuales y casos prácticos para reforzar la comprensión del curso. Después de responder, muestra la solución correcta y una explicación del concepto.

Es un material de estudio independiente: no contiene preguntas oficiales del examen, no sustituye las actividades prácticas del curso y no garantiza una certificación.

## Contenido

El banco contiene 70 preguntas:

| Módulo | Tema | Preguntas |
| --- | --- | ---: |
| 1 | Introducción a la ciberseguridad | 14 |
| 2 | Ataques, conceptos y técnicas | 20 |
| 3 | Protección de datos y privacidad | 18 |
| 4 | Protección de la organización | 12 |
| 5 | Tu futuro en ciberseguridad | 6 |

Los temas incluyen identidad y huella digital, datos organizacionales, tríada CIA, atacantes, malware, ingeniería social, vulnerabilidades, exploits, privacidad, MFA, cifrado, copias de seguridad, VPN, firewalls, IDS/IPS, defensa en profundidad, Cisco Talos, hacking ético y carreras profesionales.

## Estructura

`curso ciberseguridad.html` es una aplicación autocontenida e incluye:

- HTML y estilos adaptables.
- Las 70 preguntas y sus explicaciones.
- Selección por módulo y mezcla de preguntas.
- Navegación, resultados y repaso de errores.
- Guardado del progreso en el navegador.

No utiliza dependencias externas ni necesita un proceso de compilación.

## Cómo usarlo

1. Abre `curso ciberseguridad.html` con Chrome, Edge, Firefox o Safari.
2. Selecciona el curso completo o un módulo.
3. Responde y estudia la explicación mostrada.
4. Usa **Ver resultados** para consultar tu progreso.
5. Usa **Repasar errores** para volver a practicar las respuestas incorrectas.
6. Usa **Reiniciar todo** para borrar el progreso y comenzar nuevamente.

## Uso en celulares

Abre el archivo directamente en un navegador. Algunos visores integrados de WhatsApp, Google Drive, correo electrónico o administradores de archivos pueden bloquear JavaScript y dejar vacía el área de preguntas.

Si aparece una versión anterior, cierra la pestaña, vuelve a copiar el archivo actualizado y ábrelo nuevamente. Para descartar respuestas almacenadas de una versión anterior, pulsa **Reiniciar todo**.

## Progreso y privacidad

El cuestionario utiliza `localStorage` para guardar las respuestas y el orden de las preguntas únicamente en el navegador actual. No transmite información a servidores.

El progreso puede perderse si se borran los datos del navegador, se usa navegación privada o se abre el archivo en otro dispositivo.

## Formato de las preguntas

La respuesta correcta se almacena en la posición `0`; la interfaz mezcla las opciones antes de mostrarlas.

```javascript
{
  "id": 1,
  "module": 1,
  "q": "Texto de la pregunta",
  "options": [
    "Respuesta correcta",
    "Alternativa incorrecta",
    "Alternativa incorrecta",
    "Alternativa incorrecta"
  ],
  "correct": 0,
  "explanation": "Explicación educativa de la respuesta."
}
```

Al ampliar el banco se deben conservar identificadores únicos, cuatro opciones por pregunta y una sola respuesta correcta. Los distractores deben ser plausibles y la explicación debe aclarar tanto el concepto como sus límites.

## Referencias

- [Introduction to Cybersecurity — Cisco Networking Academy](https://www.netacad.com/es/courses/introduction-to-cybersecurity?courseLang=es-XL)
- [Cisco Networking Academy](https://www.netacad.com/)

## Estado actual

El proyecto dispone de 70 preguntas, cobertura de los cinco módulos, casos técnicos, diseño adaptable, resultados, repaso de errores y almacenamiento local. Está concebido como complemento del contenido y de las prácticas oficiales de Cisco Networking Academy.
