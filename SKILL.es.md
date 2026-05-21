---
name: stop-slop-es
description: Elimina los patrones típicos de escritura por IA en castellano. Úsala al redactar, editar o revisar prosa para quitar las muletillas predecibles de los LLM.
metadata:
  trigger: Redactar prosa, editar borradores, revisar textos en busca de patrones de IA
  author: Hardik Pandya (https://hvpandya.com)
  adaptación: versión en castellano del skill original `stop-slop`
---

# Stop Slop (ES)

Elimina los patrones predecibles de escritura por IA en castellano.

## Reglas base

1. **Corta el relleno.** Quita aperturas de carraspeo, muletillas de énfasis y todos los adverbios en -mente. Ver [references/phrases.es.md](references/phrases.es.md).

2. **Rompe las estructuras formulaicas.** Evita los contrastes binarios ("no X, sino Y"), las listas negativas, la fragmentación dramática, los montajes retóricos y la falsa agencia. Ver [references/structures.es.md](references/structures.es.md).

3. **Usa voz activa.** Cada frase necesita un sujeto humano haciendo algo. Nada de pasiva refleja para esconder al actor ("se cometieron errores", "se decidió que…"). Nada de objetos inanimados haciendo verbos humanos ("la decisión emerge", "los datos nos dicen").

4. **Sé concreto.** Nada de declarativas vagas ("las razones son estructurales", "las implicaciones son significativas"). Nombra la cosa concreta. Nada de extremos perezosos ("todo", "siempre", "nunca", "nadie") haciendo trabajo vago.

5. **Mete al lector en la escena.** Nada de narrador a distancia. "Tú" gana a "la gente". Lo concreto gana a lo abstracto.

6. **Varía el ritmo.** Mezcla la longitud de las frases. Dos elementos ganan a tres. Termina los párrafos de forma distinta. Nada de guiones largos (—).

7. **Confía en el lector.** Afirma directamente. Salta el suavizado, la justificación y el llevarle de la mano.

8. **Quita las frases para tatuaje.** Si suena a cita de Instagram, reescríbela.

## Comprobaciones rápidas

Antes de entregar el texto:

- ¿Algún adverbio en -mente? Mátalo.
- ¿Voz pasiva o pasiva refleja ("se hizo", "se cree que")? Encuentra al actor, ponlo de sujeto.
- ¿Algo inanimado haciendo un verbo humano ("la cultura cambia", "el mercado premia")? Nombra a la persona.
- ¿La frase abre con "Lo que…", "Cuando…", "Donde…", "Cómo…"? Reestructura.
- ¿"Lo cierto es que…", "La verdad es que…", "Cabe destacar…", "Resulta interesante…"? Corta y ve al grano.
- ¿Contraste "no es X, es Y" o "no porque X, sino porque Y"? Afirma Y directamente.
- ¿Tres frases seguidas con la misma longitud? Rompe una.
- ¿El párrafo cierra con un punchline contundente? Varía.
- ¿Guion largo (—) en algún sitio? Quítalo.
- ¿Declarativa vaga ("las implicaciones son significativas")? Nombra la implicación concreta.
- ¿Narrador a distancia ("Nadie diseñó esto", "La gente tiende a…")? Mete al lector en la escena.
- ¿Meta-uniones ("En el resto del artículo veremos…", "Como veremos a continuación…")? Borra. Deja que el texto avance.
- ¿Gerundios encadenados ("Hablando de X, planteando Y, abriendo Z")? Reescribe con verbos en forma personal.
- ¿Condicional excesivo ("cabría destacar", "podría considerarse")? Afirma o quita.

## Puntuación

Puntúa de 1 a 10 cada dimensión:

| Dimensión | Pregunta |
|-----------|----------|
| Directness | ¿Afirmaciones o anuncios? |
| Ritmo | ¿Variado o metronómico? |
| Confianza | ¿Respeta la inteligencia del lector? |
| Autenticidad | ¿Suena humano? |
| Densidad | ¿Hay algo recortable? |

Por debajo de 35/50: revisa.

## Ejemplos

Ver [references/examples.es.md](references/examples.es.md) para transformaciones antes/después.

## Licencia

MIT
