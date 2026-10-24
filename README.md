# Russo Skill

**Russo Skill** is a Codex skill for investigating an unknown mechanism, an emergent property, or an underdetermined failure without naming the answer too early.

Its central move is simple:

> Start with the observable trace. Test what may interact with what, under which conditions, and what arises between them. Name objects, properties, and form only after that.

The method separates observation from inference, correlation from interaction, and a useful working ontology from an established scientific fact. It also defines a **probe** as a sensitive intermediary, sample, or interface through which contact can leave an observable trace—not as the act of probing itself.

## Install

```bash
git clone https://github.com/123qup/russo.git ~/.codex/skills/russo-skill
```

Codex can discover the skill automatically when the request matches its scope. It can also be invoked explicitly as `$russo-skill`.

## Use it for

- an unknown mechanism;
- an emergent property;
- an underdetermined diagnosis;
- a reasoning dead end caused by a premature object model.

Do not force it onto ordinary design, creative writing, explanation, or implementation work that already has a known model.

## Method in one line

`observable trace → candidate relation → conditions → discriminating probe → interaction → what emerges between → minimal model → prediction → comparison`

The arrows are not a mandatory ladder. Branches may diverge or skip levels, and every transition needs its own evidence.

## Русская формулировка

Сначала фиксируется наблюдаемый след. Затем проверяется, что с чем может взаимодействовать, при каких условиях и что возникает именно «между». Только после этого называются объекты, свойства, форма и система.

Навык не утверждает сознание, не воспроизводит биологический мозг и не выдаёт реляционную онтологию за доказанный закон физики.

## Files

- `SKILL.md` — full method, workflow, scientific boundaries, and dialogue rules;
- `agents/openai.yaml` — Codex display metadata and automatic invocation policy.

## Origin

The skill was developed from Rus's relational method during the design of **Studio**, then independently reviewed against scientific and diagnostic failure modes.

## License

MIT. See `LICENSE`.
