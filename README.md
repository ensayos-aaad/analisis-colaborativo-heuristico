# PACHE — Protocolo de Análisis Colaborativo Heurístico
## con Validación Empírica

**Repositorio:** https://github.com/ensayos-aaad/analisis-colaborativo-heuristico

## Qué es esto

Un experimento metodológico realizado el 5–7 de abril de 2026 desde un 
pueblo de Colombia durante Semana Santa. Usando exclusivamente fuentes 
abiertas de prensa y dos sistemas de IA distintos, se construyó un modelo 
predictivo sobre la guerra EEUU-Israel vs Irán que acertó en el 91–92% 
de sus predicciones ponderadas.

El objetivo no fue predecir la guerra. Fue demostrar que un humano con 
acceso libre a internet y la disciplina de cuestionar sus propias 
conclusiones puede construir análisis estratégico de nivel experto sin 
credenciales institucionales, sin presupuesto, y en una tarde.

---

## Declaración de autoría y uso de IA

Los documentos de este repositorio fueron redactados por Claude Sonnet 4.6 
(Anthropic) siguiendo instrucciones explícitas del operador humano. El 
crédito intelectual del diseño metodológico corresponde al operador. 
Las IAs fueron instrumentos del método, no agentes autónomos.

De conformidad con las políticas de uso responsable de IA, ningún documento 
debe citarse como trabajo de autoría humana sin declarar que su redacción 
fue ejecutada por un modelo de lenguaje.

---

## IAs utilizadas

| Modelo | Sistema | Rol |
|--------|---------|-----|
| A | Claude Sonnet 4.6 Pro (Anthropic) | Modelo analítico base |
| B | Gemini (Google) | Modelo externo — aportó el concepto de Bypass estructural |
| C | Claude Sonnet 4.6 Pro | Síntesis hegeliana de A y B |
| D | Claude Sonnet 4.6 Pro | C + barrido multifuente en tiempo real |

Este experimento no compara capacidades entre IAs.
Usa la divergencia entre sistemas distintos como método de triangulación.

---

## Archivos

| Archivo | Descripción |
|---------|-------------|
| `commit_conversacion_v1.md` | Estado base — primeros 6 hilos de análisis |
| `commit_conversacion_v2.md` | Merge A+B, dialéctica hegeliana, métricas |
| `commit_conversacion_v3.md` | Modelo D, variable IRGC, Bypass, correlación |
| `commit_conversacion_v4.md` | Cierre — scoring final validado contra hechos |
| `PACHE_paper.pdf` | Resumen ejecutivo formal con declaración de autoría |

---

## Cómo replicar el experimento

### Requisitos
- Acceso a internet
- Un navegador web
- Los cuatro archivos markdown de este repositorio

### Pasos

**Paso 1 — Instrumento en contexto cero**

Abre tu navegador en modo incógnito:
- Chrome: `Ctrl+Shift+N`
- Safari: `Cmd+Shift+N`
- Firefox: `Ctrl+Shift+P`

Ve a [claude.ai](https://claude.ai). No inicies sesión. No crees cuenta.
Esto garantiza contexto cero absoluto — sin memoria ni historial previo.

**Paso 2 — Cargar el contexto**

En el prompt limpio, escribe exactamente esto:

> "Voy a compartirte tres archivos README que son commits de un 
> experimento de análisis. Léelos en orden: v1, v2, v3. Cuando termines, 
> confirma que tienes el contexto completo y dime en una línea cuál es 
> la predicción central del Modelo D."

Pega el contenido de los archivos v1, v2 y v3 en orden.
Espera a que Claude confirme que entendió el contexto.

**Paso 3 — Verificar o aplicar**

*Para verificar el experimento original:*
Busca en prensa qué ocurrió el 6 de abril de 2026 con el plazo de Trump 
sobre el Estrecho de Ormuz. Díselo a Claude y pídele que calcule el 
score ponderado usando la sección 6 del commit v3.

*Para aplicar el método a un problema nuevo:*
Sigue el mismo proceso — fuentes abiertas, dos IAs distintas, 
triangulación dialéctica, predicciones verificables, scoring empírico.

---

## El método en una frase

**Orientación humana → Triangulación multi-IA → Síntesis dialéctica → 
Actualización iterativa → Validación empírica.**

El humano orienta y valida. La IA triangula y sintetiza.
La inteligencia está en el espacio entre los dos.

---

## Resultados

| Modelo | IA | Score | Nota |
|--------|-----|-------|------|
| A | Claude Sonnet 4.6 | 92% | Ventaja temporal de 1 día vs B |
| B | Gemini | 67.5% | Aportó el concepto más valioso (Bypass) |
| C | Claude Sonnet 4.6 | ~88% | Síntesis — depende de A y B |
| D | Claude Sonnet 4.6 | ~91% | No posible sin el Bypass de B |

Los scores no son comparables directamente — el Modelo A tuvo 
acceso a 24 horas más de información que el Modelo B.

---

## Referencia conceptual

*La Gran Apuesta* — Michael Lewis (2010) / Adam McKay (2015).
Misma estructura: datos públicos + método + tolerancia a la incertidumbre 
= hipótesis probabilista accionable.

---

## Licencia

CC0 1.0 Universal — Dominio público.
Sin restricciones. Sin atribución requerida.
Usa, adapta, replica, mejora — sin pedir permiso.

---

*Sesión ID: IRAN-TACO-COP-HISTORIA-HEURISTICA-20260405*  
*Hash: PACHE-SCORING-FINAL-TACO-PARCIAL-20260407-MADRUGADA*
