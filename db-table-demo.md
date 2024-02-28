| Field           | Data Type | Required/Not-required | Default Value | Description                                            |
|-----------------|-----------|-----------------------|---------------|--------------------------------------------------------|
| ID              | INT       | NOT NULL              |               | Identificatore univoco dell'auto                       |
| Marca           | VARCHAR   | NOT NULL              |               | Marca dell'auto                                        |
| Modello         | VARCHAR   | NOT NULL              |               | Modello dell'auto                                      |
| Anno            | INT       | NOT NULL              |               | Anno di produzione dell'auto                           |
| Chilometraggio  | INT       | NULL                  | 0             | Chilometraggio dell'auto al momento della vendita      |
| Prezzo          | DECIMAL   | NOT NULL              |               | Prezzo di vendita dell'auto                            |
| Colore          | VARCHAR   | NULL                  |               | Colore dell'auto                                       |
| Tipo Carburante | VARCHAR   | NOT NULL              |               | Tipo di carburante utilizzato dall'auto                |
| Trasmissione    | VARCHAR   | NOT NULL              |               | Tipo di trasmissione dell'auto (Manuale/Automatica)    |
| Stato           | VARCHAR   | NOT NULL              | 'Disponibile' | Stato attuale dell'auto (Disponibile, Venduta) |
| Descrizione     | TEXT      | NULL                  |               | Descrizione dell'auto                                  |
| Data Inserimento| DATE      | NOT NULL              | CURRENT_DATE  | Data di inserimento dell'annuncio                      |
| Data Vendita    | DATE      | NULL                  |               | Data di vendita dell'auto                              |
| Prenotata       | BOOL/INT   | NOT NULL              | FALSE/ ( 0 )         | Indica se l'auto è stata prenotata                    |
