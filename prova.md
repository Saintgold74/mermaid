# Il mio documento

Ecco un diagramma di esempio:

```mermaid
graph TD
    A[Inizio] --> B[Processo]
    B --> C{Decisione}
    C -->|Sì| D[Risultato 1]
    C -->|No| E[Risultato 2]
sequenceDiagram
    Utente->>Sistema: Richiesta
    Sistema->>Database: Query
    Database->>Sistema: Risultato
    Sistema->>Utente: Risposta
