# Specification

What {{Project}} does, as it stands, by example. Roles and entities are in the [README](../../README.md); the reasons are in the [decisions](../decisions.md).

Each feature lists its rules. A rule has an id, `<Feature>.<NN>`, that is never reused, and an example. Each rule is translated into a test; one that can't be tested automatically says how it is checked.

## {{Feature}}

- {{Situation}}: {{what happens}} ({{Feature}}.01)

Example:

```
Given {{state}}
When {{action}}
Then {{result}}
```

## Narrative

{{A story of one Role using the features in order, each named like [Feature].}} One or more end-to-end tests follow it.
