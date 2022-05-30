# USED CARS

## Modello: Car

## Table: Cars

- id:                       bigint          PRIMARYKEY(NOTNULL, AUTOINCREMENTS, UNIQUE)
- modello:                  VARCHAR(100)    NOTNULL
- cilindrata:               SMALL           NOTNULL
- cavalli:                  FLOAT(4, 2)     NULL
- versione:                 VARCHAR(100)    NULL
- marca:                    VARCHAR(50)     NOTNULL
- anno:                     DATE            NOTNULL
- km_percorsi:              MEDIUMINT       NOTNULL
- revisionata:              TINYINT         NULL
- prezzo_vendita:           DECIMAL(9, 2)   NOTNULL
- finanziamento:            TINYINT         NULL
- carrozzeria:              VARCHAR(100)    NULL
- kw:                       FLOAT(6, 2)     NULL
- per_neopatentati:         TINYINT         NULL
- carburante:               VARCHAR(50)     NULL
- cambio:                   VARCHAR(30)     NULL
- numero_porte:             TINYINT         NULL
- numero_di_posti:          TINYINT         NULL
- venditore:                VARCHAR(100)    NULL
- condizione_veicolo:       VARCHAR(100)    NULL
- dotazioni:                TEXT            NULL
- colore_carrozzeria:       VARCHAR(50)     NULL
- tipo_vernice:             VARCHAR(50)     NULL
- colore_interni:           VARCHAR(50)     NULL
- materiale_interni:        VARCHAR(50)     NULL
- garanzia:                 TINYINT         NULL
- tagliandi_certificati:    TINYINT         NULL
- classe_emissione:         VARCHAR(50)     NULL
- filtro_antiparticolato:   TINYINT         NULL
- immagine:                 VARCHAR(255)    NULL
- quantità:                 TINYINT         NOTNULL DEFEULT(0)
- disponibile:              TINYINT         NOTNULL

