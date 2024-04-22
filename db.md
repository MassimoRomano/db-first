# Esercizio
Modellare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

DB_NAME: Library

Table name: autoUsate


- id | INT | NOT NULL | UNIQUE | AUTO_INCREMENT
- venditore | VARCHAR(100) |NULL
- image | VARCHAR(255) | NOT NULL
- casa madre | VARCHAR(50) | NOT NULL
- modello auto | VARCHAR(50) | NOT NULL
- tipo veicolo | VARCHAR(50) | NOT NULL
- carburante | VARCHAR(20) | NOT NULL
- cambio (automatica-manuale) | VARCHAR (20) | NOT NULL
- km | MEDIUMMINT | NUll
- colore | VARCHAR(30) | NOT NULL
- porte |TINYINT| NULL
- condizioni | TEXT | NOTNULL
- anno immatricolazione | YEAR | NOT NULL
- disponibile -> DATETIME | NULL
- prezzo | MEDIUMINT | NOTNULL
- note | TEXT