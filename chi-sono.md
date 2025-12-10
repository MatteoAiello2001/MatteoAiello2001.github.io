---
layout: default
title: Chi Sono
---

# Chi Sono

Ciao, mi chiamo Matteo e questo è il mio wiki personale!

```md
# Info SQL

Di seguito il codice SQL di esempio:

```sql
-- x creare una nuova tabella
CREATE TABLE SafetyFepaCopy.dbo.InfoDoc (
  id INT IDENTITY(1,1) PRIMARY KEY,
  codice VARCHAR(255),
  idTipologieDocumentali INT,
  idServizi INT
);

-- esempio SELECT
SELECT
  CASE 
    WHEN condizione1 THEN risultato1
    WHEN condizione2 THEN risultato2
    ELSE risultato_default
  END AS NomeColonna
FROM NomeTabella;
