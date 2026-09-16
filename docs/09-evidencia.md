# 09 — Evidencia, conocimiento e inteligencia artificial

## Objetivo

Manual de Vida debe poder explicar de dónde proviene una afirmación educativa y distinguir entre conocimiento respaldado, interpretación, hipótesis y propuesta pedagógica.

## Jerarquía conceptual

El sistema deberá separar como mínimo:

1. **Fuente:** documento, organismo, estudio u otro material de referencia.
2. **Afirmación:** qué dice la fuente.
3. **Evidencia:** qué tipo de respaldo existe y cuáles son sus límites.
4. **Interpretación:** cómo se entiende esa evidencia dentro del proyecto.
5. **Propuesta pedagógica:** cómo convertirla en una experiencia de aprendizaje.
6. **Hipótesis:** aquello que todavía debe probarse.
7. **Experimento:** prueba realizada para aprender sobre el diseño.

## Familias de fuentes prioritarias

- UNICEF y organismos especializados en derechos, bienestar y educación de niños y adolescentes;
- UNESCO y organismos educativos internacionales;
- autoridades públicas y sistemas educativos relevantes;
- literatura científica, revisiones sistemáticas y metaanálisis cuando estén disponibles;
- especialistas y organizaciones profesionales pertinentes al tema;
- recursos educativos evaluados;
- referencias culturales y narrativas, separadas explícitamente de la evidencia científica.

## Primer conjunto de referencias incorporado

### UNICEF — educación digital

La *Digital Education Strategy 2025–2030* orienta la educación digital hacia resultados de aprendizaje, equidad y enfoques humanos. También enfatiza experiencias sociales, lúdicas, creativas y prácticas, y plantea que lo digital debe complementar —no sustituir— juego, actividad física e interacción presencial. citeturn0search8turn0search11

### UNICEF — IA y niñez

La *Guidance on AI and children*, versión 3.0 (2025), establece requisitos para sistemas de IA centrados en niños, incluyendo seguridad, privacidad, no discriminación, transparencia, rendición de cuentas, bienestar, inclusión y preparación para el entorno de IA. También aborda riesgos emergentes de compañeros de IA. citeturn0search3

UNICEF Uruguay también destaca oportunidades y riesgos específicos del uso de IA por niños, niñas y adolescentes, incluyendo sesgos y la necesidad de acompañamiento informado. citeturn0search1

### UNICEF — juego

UNICEF considera el juego una vía fundamental de desarrollo y aprendizaje, y señala su relación con habilidades cognitivas, sociales y emocionales. Para Manual de Vida, esto respalda investigar el juego como componente pedagógico, sin convertirlo en una simple técnica de retención digital. citeturn0search10turn0search15

### UNESCO — alfabetización en IA

El *AI Competency Framework for Students* propone progresiones para que los estudiantes comprendan, apliquen y creen con IA, con énfasis en pensamiento centrado en las personas, ética, técnicas y diseño de sistemas. Esto puede informar una futura dimensión de alfabetización en IA adaptada al desarrollo. citeturn0search5turn0search14

### Referencias narrativas — Inside Out / Intensa-Mente

*Inside Out* e *Inside Out 2* pueden estudiarse como referencias de diseño narrativo: convierten conceptos abstractos relacionados con emociones, memoria, imaginación, identidad y adolescencia en personajes y espacios visuales. Pixar describe explícitamente estos elementos dentro del universo narrativo de las películas. citeturn1search1turn1search2

Estas obras **no se consideran evidencia científica**. Sirven para investigar cómo hacer visible y comprensible un concepto abstracto. Las afirmaciones psicológicas deberán contrastarse con fuentes independientes.

## Arquitectura conceptual de IA

La IA deberá funcionar como una capa sobre conocimiento controlado:

```text
Fuentes
  ↓
Ingesta y normalización
  ↓
Conocimiento estructurado
  ↓
Indexación / recuperación
  ↓
Evidencia relevante
  ↓
Motor pedagógico y reglas de seguridad
  ↓
Modelo de IA
  ↓
Experiencia adaptada al usuario
```

Esta arquitectura es una hipótesis de diseño y deberá validarse antes de implementarse.

## Qué podría hacer la IA

- explicar un concepto con lenguaje apropiado para la etapa del usuario;
- proponer ejemplos;
- formular preguntas;
- transformar una situación cotidiana en una actividad educativa;
- ofrecer diferentes formas de practicar;
- ayudar a revisar una decisión o un error;
- conectar una pregunta con contenido educativo pertinente;
- adaptar la dificultad sin alterar el fundamento factual.

## Qué no debería hacer por defecto

- diagnosticar al usuario;
- sustituir a un profesional;
- decidir por el niño;
- presentar una hipótesis como hecho;
- inventar fuentes;
- interpretar una emoción como diagnóstico;
- mantener conversaciones diseñadas para crear dependencia emocional;
- solicitar información personal innecesaria;
- ocultar que una respuesta proviene de un sistema de IA cuando esa distinción sea relevante.

## Respuestas fundamentadas

Cuando una respuesta dependa de evidencia externa, el sistema deberá poder identificar internamente la fuente utilizada y, cuando la experiencia lo permita, facilitar una explicación de procedencia adecuada a la edad.

## Temas sensibles

En temas de alto riesgo, la IA deberá operar con reglas más restrictivas, contenido previamente validado, rutas de ayuda y mecanismos de escalamiento definidos.

## Evolución

La base de conocimiento deberá poder actualizarse sin depender de reentrenar todo el sistema. Los cambios importantes deberán conservar trazabilidad sobre qué fuente cambió, qué contenido fue afectado y qué versión del sistema lo utiliza.

## Estado

**Versión 0.2.** Arquitectura conceptual actualizada con el primer conjunto de fuentes y referencias narrativas. No constituye todavía una especificación técnica ni autoriza el uso de IA con menores reales.
