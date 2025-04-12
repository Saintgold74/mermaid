sequenceDiagram
    Utente->>Sistema: Richiesta
    Sistema->>Database: Query
    Database->>Sistema: Risultato
    Sistema->>Utente: Risposta
