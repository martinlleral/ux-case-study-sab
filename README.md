# Caso de Estudio UX: Sistematización Ágil de una Cooperativa Musical

## Contexto

Una cooperativa musical de **21 integrantes** (17 músicos, 2 bailarines, 1 técnico, 1 productor) en La Plata, Argentina, con ciclos regulares de shows en vivo y una estructura organizativa basada en **sociocracia** (8 círculos: General, Ciclo, Artística, Finanzas, Managereo, Comunicación, Merch, Técnica).

La organización había implementado parcialmente un modelo sociocrático, pero sin herramientas digitales que lo sostengan. Las decisiones se perdían en WhatsApp, los roles no estaban claros, y los dos co-fundadores cargaban con la mayor parte del trabajo operativo.

---

## Desafío

Los líderes expresaban desgaste real:

> *"Es un delirio. Tengo una banda de mensajes de gente que debemos plata acá, que debemos plata allá..."*
> — Co-fundador A (finanzas)

> *"La toma de decisiones sigue siendo el punto de fricción más alto, solo que va mutando"*
> — Co-fundador B (dirección artística)

**Problemas identificados:**
- Reuniones de 2 horas sin output registrado
- Decisiones que se rediscutían porque nadie recordaba lo acordado
- Roles difusos: sin facilitadores, sin secretarios, solo coordinadores de nombre
- Comunicación interna deficiente: miembros se enteraban de fechas por el flyer público
- Sobrecarga operativa en los 2 co-fundadores
- Herramientas existentes (calendar, docs) que nadie usaba

---

## Mi rol

**UX Researcher + Facilitador + Product Owner**

Mi involucramiento con la organización comenzó en el Q4 de 2025, asistiendo a shows, ensayos y reuniones como observador participante. Durante varios meses escuché, registré y busqué entender cómo funciona el sistema desde adentro antes de proponer cualquier intervención. Recién con ese entendimiento profundo pasé a aplicar técnicas de investigación específicas y diseñar soluciones que respeten la cultura del grupo.

---

## Metodología

### 1. Observación participante (Q4 2025 — feb 2026)
Durante ~4 meses asistí a ensayos, shows y reuniones de círculos como insider, sin intervenir ni proponer cambios. Esto me permitió observar dinámicas que no aparecen en entrevistas: quién habla, quién calla, cómo se toman las decisiones informales, qué rituales son sagrados. En febrero sistematicé todo el registro acumulado: notas de campo, conversaciones informales y patrones observados.

### 2. Entrevistas semi-estructuradas de profundidad (marzo 2026)
Con el entendimiento construido durante la observación, diseñé guiones específicos para profundizar en los ejes críticos identificados.

Realicé **2 entrevistas con los co-fundadores** — las dos personas con mayor carga operativa y visión estratégica:

| Entrevistado | Duración | Modalidad | Foco |
|-------------|----------|-----------|------|
| Co-fundador A (finanzas) | 45 min | Videollamada | Carga operativa, timing, adopción |
| Co-fundador B (dirección artística) | 90 min | Presencial | Valores, fricción, visión, rituales |

**Guión semi-estructurado** con ejes: carga operativa, percepción de la sociocracia, rituales valorados, visión a 3 años, miedos sobre la sistematización.

### 3. Análisis cruzado (marzo 2026)
Analicé cada entrevista individualmente (tabla de dimensiones × hallazgos × citas textuales), y luego crucé los resultados para identificar **convergencias** (6 puntos de acuerdo) y **divergencias** (4 tensiones productivas).

### 4. Diseño de encuesta cuantitativa-cualitativa (marzo 2026)
Diseñé una encuesta de 6 preguntas para los 21 miembros: "Radiografía organizacional". Anónima, < 3 minutos, optimizada para celular. Las categorías de la pregunta de fricciones salieron directamente de los hallazgos de las entrevistas.

---

## Hallazgos clave

### 6 Convergencias (ambos co-fundadores coinciden)

| Tema | Implicancia |
|------|-------------|
| Desgaste operativo real | Hay urgencia genuina. No es capricho, es dolor. |
| Adopción gradual | El sistema debe entrar sin fricción. Nada de Big Bang. |
| Abril como ventana | Marzo = discovery. Sprint 1 real en abril. |
| Encuesta como primer paso | Artefacto de entrada con menor resistencia. |
| Valor de la transparencia | Ambos piden visibilidad. El sistema centralizado responde esto. |
| Confianza mutua | La alianza fundadora está sólida. Ventaja enorme. |

### 4 Divergencias (tensiones productivas)

| Tema | Co-fundador A | Co-fundador B | Lectura |
|------|--------------|--------------|---------|
| Velocidad | Cauteloso: "con paciencia" | Impulsivo: mete cambios "por la ventana" | El sistema debe dar estructura a la impulsividad sin matarla |
| Estructura | "Que funcione empresa" | "Que no se vuelva frío" | La solución debe ser **estructura con alma** |
| Círculos | Trabaja con la estructura actual | Propone fusionar áreas | Validar con encuesta |
| Delegación | Maneja las finanzas solo | No quiere abrir hasta cooperativa formal | Riesgo operativo: dependencia de 1 persona |

### 5 Descubrimientos no anticipados

1. **El "producto" no es la música.** Es la experiencia de encuentro cultural, la "sensación de otro tiempo". Esto redefine cómo medir el éxito.

2. **La paradoja de la sistematización.** Hay reclamo de sistema, pero las herramientas existentes (calendar, docs) no se usan. El problema no es de herramienta sino de **hábito y cultura de adopción**.

3. **Los rituales son activos estratégicos.** Bailar con el público post-show es un diferenciador de marca que genera conexión genuina. Proponer sistematizarlo (rotación de 7 personas) es un ejemplo de "ritualizar sin encorsetar".

4. **La música propia como techo de crecimiento.** Cuando tengan canciones propias que el público cante, "no tiene techo". Norte estratégico a largo plazo.

5. **Riesgo de dependencia de personas clave.** Las proyecciones a futuro de algunos integrantes sugieren que la organización necesita funcionar sin depender de ninguna persona en particular. Esto da urgencia a la institucionalización de procesos y conocimiento.

---

## Del hallazgo a la acción

### User Stories deducidas (9)

Cada user story fue deducida directamente del análisis cruzado, con trazabilidad al problema original y citas textuales que la fundamentan.

#### Gobernanza

| ID | User Story | Prioridad | Sprint |
|----|-----------|-----------|--------|
| US-GOB-01 | Como integrante, quiero consultar un registro centralizado de decisiones para evitar rediscutir los mismos temas | Crítica | 1 |
| US-GOB-02 | Como coordinador, quiero una tarjeta con mis responsabilidades para saber qué hacer en cada reunión | Alta | 1 |
| US-GOB-03 | Como miembro, quiero que cada área reporte mensualmente sus logros para tener visibilidad del avance | Alta | 2 |

#### Operaciones

| ID | User Story | Prioridad | Sprint |
|----|-----------|-----------|--------|
| US-OPS-01 | Como coordinador del ciclo, quiero una checklist de cierre de cada show para que "terminado" signifique lo mismo para todos | Crítica | 1 |
| US-OPS-02 | Como coordinador, quiero enviar un link al artista invitado con toda la info para no repetir por WhatsApp | Media | 2 |
| US-OPS-03 | Como miembro, quiero que los círculos estén organizados sin redundancia | Alta | 2 |

#### Cultura y Feedback

| ID | User Story | Prioridad | Sprint |
|----|-----------|-----------|--------|
| US-CUL-01 | Como miembro, quiero un canal anónimo para expresar mis opiniones para que mi incomodidad se transforme en mejora | Crítica | 1 |
| US-CUL-02 | Como integrante, quiero que haya un momento ritualizado post-show para mantener el diferenciador de marca | Media | 2 |

#### Cerebro Digital

| ID | User Story | Prioridad | Sprint |
|----|-----------|-----------|--------|
| US-DIG-01 | Como secretario, quiero generar el acta desde el audio para no perder tiempo escribiendo | Alta | 1 |

### Priorización MoSCoW

- **Must Have (Sprint 1):** Bitácora de decisiones, Checklist DoD, Sensor de percepciones, Tarjetas de rol, Actas IA
- **Should Have (Sprint 2):** Reporte mensual, Kit de invitado, Reorganización de círculos, Ritual post-show
- **Could Have (Sprint 3+):** Interfaz audio-first (WhatsApp → Notion), Motor de puntos automático
- **Won't Have (ahora):** App propia, integración con ticketera

### Trazabilidad problema → solución

| Problema | User Story | Sprint |
|----------|-----------|--------|
| Decisiones perdidas en WA | US-GOB-01 | 1 |
| Roles difusos | US-GOB-02 | 1 |
| Reuniones sin output | US-OPS-01, US-DIG-01 | 1 |
| Feedback en rumores | US-CUL-01 | 1 |
| Sobrecarga en líderes | US-DIG-01, US-OPS-01 | 1 |
| Comunicación deficiente | US-GOB-03, US-OPS-02 | 2 |
| Sociocracia a medias | US-OPS-03, US-GOB-02 | 1-2 |
| Herramientas sin adoptar | US-DIG-02 (interfaz invisible) | 3 |

---

## Roadmap

### Fase 0: Discovery (Q4 2025 — marzo 2026)
Escuchar antes de intervenir. Construir entendimiento y legitimidad con datos.
- Observación participante durante ~4 meses (shows, ensayos, reuniones)
- Sistematización del registro acumulado (febrero)
- Entrevistas semi-estructuradas con stakeholders clave (marzo)
- Diseño y distribución de encuesta a los 21 miembros
- Análisis cruzado y presentación de informe en reunión general

### Sprint 1: "Claridad" (abril, semanas 1-2)
Sprint Goal: *Las decisiones quedan escritas, los shows terminan con registro, y cada coordinador sabe qué le toca.*
- Bitácora de Decisiones (DB Notion)
- Checklist de Cierre de Show (Definition of Done)
- Sensor de Percepciones v1 (encuesta post-show recurrente)
- Tarjetas de Rol para coordinadores
- Prompt maestro IA para actas (prueba con 1 círculo)

### Sprint 2: "Ritmo" (abril sem. 3 — mayo)
- Reporte mensual de incrementos por área
- Kit de invitado (página pública Notion)
- Propuesta de reorganización de círculos (basada en datos)
- Ritual post-show sistematizado
- Actas IA en producción para todos los círculos

### Sprint 3+: "Escala" (junio en adelante)
- Interfaz audio-first (WhatsApp → Notion)
- Motor de puntos/distribución automática
- Radar de subsidios con IA

---

## Resultados e impacto

| Métrica | Antes | Después | Cambio |
|---------|-------|---------|--------|
| Duración de reuniones | 2 horas | 45 minutos | **-56%** |
| Tiempo de actas | 1-2 días (manual) | < 10 minutos (IA) | **-95%** |
| Horas humanas ahorradas/semana | — | **42 horas** (2h × 21 personas) | — |
| Decisiones re-discutidas/mes | 5-8 | 0-1 | **-90%** |
| Onboarding de invitados | 5-10 mensajes WA | 1 link | **-80%** |
| Canales de comunicación | 210 (sin estructura) | 42 (con círculos) | **-80%** |

---

## Marco teórico

- **Número de Dunbar:** Una organización de 21 personas está en la zona de transición (entre el grupo íntimo de 15 y el clan de 50). Requiere estructura formal para funcionar, pero puede mantener relaciones de confianza directa.

- **Efecto Ringelmann:** En grupos de 8+, la responsabilidad se diluye. Los círculos sociocráticos de 3-5 personas contrarrestan este efecto.

- **Sociocracia 3.0:** La organización había adoptado la estructura de círculos pero sin los roles de soporte (facilitador, secretario). Completar la implementación fue clave.

- **Fórmula de canales de comunicación:** n×(n-1)/2. Con 21 personas sin estructura = 210 canales posibles. Con 8 círculos de ~3-5 personas = ~42 canales. Reducción del 80% en complejidad comunicacional.

---

## Lecciones aprendidas

1. **El problema nunca es la herramienta.** El calendar existía y nadie lo usaba. La adopción es un problema de cultura y hábito, no de software.

2. **Investigar antes de proponer.** Las 2 entrevistas revelaron que el "producto" real de la organización no era lo que todos asumían. Sin esa investigación, habríamos diseñado para el problema equivocado.

3. **Estructura con alma.** La tensión entre "que funcione como empresa" y "que no se vuelva frío" se resolvió diseñando sistemas que respetan los rituales existentes. Sistematizar no es burocratizar.

4. **El insider tiene ventaja.** La observación participante reveló dinámicas que ninguna entrevista hubiera capturado. Ver quién habla, quién calla, y cómo se toman las decisiones informales fue crucial.

5. **Adopción gradual, no Big Bang.** Ambos co-fundadores coincidieron: el equipo está sobrecargado. Forzar un cambio masivo habría generado rechazo. Cada sprint introduce 1-2 cambios visibles.

---

## Competencias demostradas

| Competencia | Evidencia |
|-------------|-----------|
| **UX Research** | Entrevistas semi-estructuradas, observación participante, análisis cruzado, diseño de encuesta |
| **Product Ownership** | Product Backlog con 9 User Stories priorizadas, Sprint Planning, Definition of Done |
| **Facilitación** | Gestión de stakeholders con visiones divergentes, adopción gradual |
| **Service Design** | Diseño de flujos (audio → IA → acta → Notion), blueprint de servicios internos |
| **Scrum** | Sprint Goals, roadmap de 3 sprints, retrospectiva implícita en análisis de divergencias |
| **IA aplicada** | Prompt maestro para actas automáticas (< 10 min), interfaz audio-first |

---

## Autor

**Martín Lleral** — Lic. en Antropología (UNLP) | Co-fundador de TRAMA | Sistematización ágil para organizaciones

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mart%C3%ADn-lleral-9a57a475)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)](https://github.com/martinlleral)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:martinlleral@gmail.com)
