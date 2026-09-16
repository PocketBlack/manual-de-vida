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

## Fuentes

Se priorizarán fuentes institucionales y científicas apropiadas al tema, incluyendo organismos internacionales, autoridades públicas, literatura académica y materiales educativos evaluados.

Cada contenido relevante deberá conservar referencia suficiente para poder volver a la fuente original.

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

**Versión 0.1.** Arquitectura conceptual. No constituye todavía una especificación técnica ni autoriza el uso de IA con menores reales.
