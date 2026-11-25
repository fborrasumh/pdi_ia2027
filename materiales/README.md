# Materiales del curso «Del prompt al DOI»

Ficheros de entrada para cada app del curso, organizados por sesión y por app. Todos siguen **un hilo común**:

- **Sesión 2 (docencia):** la asignatura ficticia *Bioestadística* (1.º del Grado en Enfermería, Universidad Iberoamericana de Ejemplo). La salida de cada app alimenta la siguiente.
- **Sesión 3 (investigación):** el conjunto de datos abierto de diabetes en 768 mujeres pima (NIDDK / UCI), desde la revisión de la literatura hasta la elección de revista.
- **Sesión 4 (tu app):** una calculadora de pruebas diagnósticas para la misma asignatura.

Cada carpeta de app tiene un `LEEME.md` con qué subir, qué escribir en cada campo y el flujo de pantallas. Los participantes pueden sustituir estos ficheros por su propio material.

```
sesion01/  obligatorias/  Cuentas_y_clave · Practica_de_prompts      opcionales/ (sin apps)
sesion02/  obligatorias/  SyllabusAI · ExamForge · AntiConvocatorIA · CriterIA · TFG_Evaluator
           opcionales/    AulIA · CorrigIA · MentorIA · Evaluador_Oral · ConvocatorIA
sesion03/  obligatorias/  Doctoralia · Humanitas · CuadernIA · NarrativIA · RefinIA · RevistaFit
           opcionales/    PRISMIA · Publication_Radar · GrantWriter · Autoresearch · ProcedencIA
sesion04/  obligatorias/  ForjaIA
           opcionales/    TutorIA · ClarIA · Generator
```

## Comprobación en las apps (23/11/2026)

Probado en Chrome con clave de OpenAI (modelo por defecto de cada app). «Completa» = flujo ejecutado con IA hasta el resultado; «Lectura» = la app abre y lee los ficheros (sin lanzar la IA).

| Sesión | App | Prueba | Resultado |
|---|---|---|---|
| 2 | SyllabusAI | Completa | Guía generada; revisión de calidad 90/100 (0 errores, 2 avisos). |
| 2 | ExamForge | Completa | 12 exámenes, 120 preguntas, 119 con cita verificada en los apuntes. |
| 2 | AntiConvocatorIA | Completa | 6 exámenes leídos; previsibilidad 39 %; tabla, sorteo y examen redactado. |
| 2 | CriterIA | Completa | Declaración generada; las dos referencias reales salen «Existe» y la inventada «No la encuentro» (tras corregir la app). |
| 2 | TFG Evaluator | Completa | Nota 6,49/10; 21 de 21 citas verificadas (fidelidad 100 %), tras corregir el verificador de la app. |
| 2 | AulIA · CorrigIA · OralIA · ConvocatorIA | Lectura | Leen los ficheros (apuntes, 3 copias manuscritas, cuaderno, exámenes). |
| 2 | MentorIA | — | Solo texto pegado; no lee ficheros. |
| 3 | Doctoralia | Completa | Borrador rápido: 81 papers, 30 citas, 4700 palabras, 100 % de citas resueltas. |
| 3 | Humanitas | Completa | 74 obras recuperadas (39 monografías y capítulos); redacción en curso al cerrar la prueba. |
| 3 | CuadernIA | Completa | Cuaderno de 8 secciones ejecutado; detecta los ceros como perdidos; verificación 43/100. |
| 3 | NarrativIA | Completa | Resultados redactados; revisión 100/100, 26/26 cifras respaldadas. |
| 3 | RefinIA | Completa | 6 comentarios: AUC distinto en resumen y resultados, lenguaje causal, sin validación… |
| 3 | RevistaFit | Completa | Revistas candidatas con evidencia de OpenAlex (Scientific Reports, BMJ Open…). |
| 3 | GrantWriter · Autoresearch | Lectura | Leen bases, idea y borrador. |
| 3 | PRISMIA | — | Pide claves de tres proveedores distintos. |
| 3 | Publication Radar | — | No usa ficheros. |
| 3 | ProcedencIA | Sellado sin IA (25/11/2026) | 5 puntos de control sellados, cadena íntegra; la comparación 2→3 muestra la frase inventada; declaración generada (ChatGPT, edición de estilo, Discusión). |
| 4 | ForjaIA | Completa hasta autoría | Entiende el encargo y el cuaderno y propone las preguntas. No se construyó la app. |
| 4 | TutorIA · ClarIA · Generator | Lectura | Leen el tema, el PowerPoint con notas y la guía docente. |

## Origen de los datos

- Pima Indians Diabetes Database: National Institute of Diabetes and Digestive and Kidney Diseases, difundido por el UCI Machine Learning Repository.
- El resto del material (asignatura, exámenes, TFG, manuscrito, copias manuscritas, convocatoria) es **ficticio**, creado para el curso. Los fallos plantados para las apps de revisión se describen en cada `LEEME.md`.
