
D## Stack tecnológico

| Capa | Tecnología | Justificación |
|---|---|---|
| Estructura | HTML5 | Sin dependencias, abre en cualquier navegador |
| Estilos | CSS3 inline | Todo en un archivo, sin compilación |
| Lógica | JavaScript vanilla | Sin frameworks, cero configuración |
| Tipografía | Google Fonts (CDN) | Una línea de código, resultado visual profesional |
| Imágenes | URLs públicas | Sin hosting propio ni assets locales |

---

## Motor de matching

Cada respuesta suma puntos a uno o varios artistas según pesos predefinidos. Al terminar las 5 preguntas, se recorre el objeto de puntajes y se retorna el artista con el mayor número. Menos de 30 líneas de JavaScript.

```js
scores = { badbunny: 0, karolg: 0, shakira: 0, sodastereo: 0, juanes: 0 }

// Cada respuesta ejecuta algo como:
scores['karolg'] += 3;
scores['badbunny'] += 1;

// Al final:
resultado = Object.keys(scores).reduce((a, b) => scores[a] > scores[b] ? a : b)
```

---

## Criterios de éxito

### Mínimos (debe cumplirse)

| Criterio | Descripción |
|---|---|
| Flujo sin fricciones | El usuario completa el cuestionario de inicio a fin sin errores ni pasos confusos |
| Tiempo de sesión | El cuestionario se completa en menos de 90 segundos |
| Resultados creíbles | Al menos 8 de cada 10 usuarios sienten que el artista asignado tiene sentido con sus respuestas |
| Diversidad de resultados | Los 5 artistas son alcanzables; ninguno acapara todos los resultados |
| Sin bugs críticos | El prototipo no se rompe durante la demo |

### Ideales (eleva el proyecto)

| Criterio | Descripción |
|---|---|
| Diseño atractivo | Interfaz con identidad visual coherente; la tarjeta de resultado genera deseo de compartir |
| Reacción espontánea | Al menos una persona quiere mostrarle el resultado a alguien sin que se lo pidan |
| Propuesta articulada | La presentación comunica claramente el valor para Spotify o YouTube en menos de 2 minutos |

---

## Cronograma

| Día | Entregable |
|---|---|
| Día 1 | Estructura HTML, 5 preguntas definidas, CSS básico funcionando |
| Día 2 | Lógica de matching completa, pantalla de resultado, 5 artistas perfilados |
| Día 3 | Pulir visual, probar con personas reales, ajustar pesos según feedback |

---

## Visión a futuro

Con la PoC validada, el proyecto escala en dos direcciones:

1. **Técnica:** migrar a React + Vite, ampliar el catálogo de artistas, añadir URL compartible y diseño mobile-first más elaborado
2. **Comercial:** propuesta de integración con Spotify o YouTube Music como feature de descubrimiento emocional, campaña de marca o herramienta de engagement

El archivo HTML entrega la evidencia conceptual necesaria para ese pitch — sin prometer más de lo que se puede construir en el tiempo disponible.

---

> **Para el YTech:** abres el archivo en el navegador, le pasas el celular a alguien, responde 5 preguntas en 90 segundos y ve su artista. Eso es suficiente para vender la idea.
