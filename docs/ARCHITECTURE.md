```mermaid
graph LR
  A[Client] -->|Request|> B[Server]
  B -->|Response|> A
  B -->|Database Query|> C[Database]
  C -->|Query Result|> B
```