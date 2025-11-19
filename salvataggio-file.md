I file si possono vedere via codice in due formati:

Hash (non è reversibile)
  SHA-256 (a9fd8b3f5176e996f0560dc4e2f59e38e69de62927ca6844f21d36055100d43d)

Codifica (refersibile)
  base64 (es. JVBERi0xLjQNCiWio4+TDQo1IDAgb2JqDQo8PC9UeXBlIC9YT2JqZWN0IC9TdWJ0eXBlIC9JbWFnZSAvV2lkdGggMTggL0hlaWdodCAxOCAQoNCnN0YXJ0eHJlZg0KNzQ2NDYNCiUlRU9GDQo=)
  quest'ultimo viene visualizzato in un file .txt con la codifica UTF-8 o ASCII
  queste ultime due codifiche permettono di visualizzare un carattere uguale a 1byte (quindi 8bit, e quindi es. 00100100)
  quindi in conclusione, se io salvo questo tipo di file .txt
    AAAAA
  sarà via codice salvato così
    0100000101000001010000010100000101000001
  e se lo codifico in base64, a detta di chatgpt, sarà una roba tipo questa
    QUFBQUE=
  (non so perchè ma è così)



