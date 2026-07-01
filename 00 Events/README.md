---
type: system
tags: [system, event-bus]
---

# Event Bus

Dit is de gedeelde event bus van het autonome kennisbrein.

## Werking

Agents schrijven events naar `pending/` en lezen events uit `pending/`.
Verwerkte events worden verplaatst naar `processed/`.

## Event Types

| Event | Gepubliceerd door | Gelezen door |
|---|---|---|
| KnowledgeDiscovered | Agent 1 | Agent 2 |
| KnowledgeStructured | Agent 2 | Agent 3, Agent 5 |
| LearningMaterialCreated | Agent 3 | — |
| GraphUpdated | Agent 4 | Alle agents |
| HypothesisCreated | Agent 5 | Agent 4 |
| KnowledgeGapDetected | Agent 5 | Agent 1 |
| ConflictDetected | Agent 4, Agent 5 | Agent 4 |

## Event Formaat

```json
{
  "event_type": "KnowledgeDiscovered",
  "agent": "Agent1-KnowledgeHunter",
  "timestamp": "2026-07-01T05:00:00Z",
  "status": "pending",
  "data": {}
}
```
