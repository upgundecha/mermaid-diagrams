```
graph LR
  A[Consumer] -- generates --> B[Pact Contract]
  B -- published to --> C[Pact Broker]
  C -- shared with --> D[Provider]
  D -- verifies against --> B
  A -- interacts with --> D
```
``` mermaid
graph LR
  A[Consumer] -- generates --> B[Pact Contract]
  B -- published to --> C[Pact Broker]
  C -- shared with --> D[Provider]
  D -- verifies against --> B
  A -- interacts with --> D
```
