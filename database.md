#concessionario

## Table Name

-macchine_usate

## Table columns

-id | PK, BIGINT, AUTO_INCREMENT, UNIQUE, NOT NULL
-nome_modello | VARCHAR(50), NOT NULL
-prima_immatricolazione | DATE
-kilometri | INT, NULL
-tipo_di_carburante | VARCHAR(20), NOT NULL
-cambio | VARCHAR(10), NULL
-potenza | VARCHAR(10), NULL
-propietari_precedenti | SMALLINT, DEFAULT(1)
-classe_veicolo | VARCHAR(50), NULL
-portiere | TINYINT, NULL
-numero_di_sedili | TINYINT, NULL
-colore_veicolo | VARCHAR(50), NULL
-motore_originale | TINYINT, NULL
-cilindrata | TINYINT, NULL
-condizioni | VARCHAR(50), NULL
-disponibile | TINYINT, DEFAULT(0)
-paese_di_origine | VARCHAR(50), NULL
-immagine | VARCHAR(255), NULL
-targa | VARCHAR(7), NULL
-numero_inventario | VARCHAR(10) NULL
-revisione | DATE, NULL
-prezzo| SMALLINIT. NULL
