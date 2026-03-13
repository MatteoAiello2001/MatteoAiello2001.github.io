



### Info generali

| Ambito | Linguaggio / DB | IDE / Strumento |
| :--- | :--- | :--- |
| DB | MySQL | MySQL Workbench |
| DB | Oracle | Oracle SQL Developer |
| DB | SQL Server | SQL Server Management Studio (SSMS) |
| BE | Java | Eclipse |
| BE | Java | NetBeans |
| BE | Java | IntelliJ IDEA |
| BE | C# | Visual Studio |
| FE | — | Visual Studio Code |







```













Ogni DB ha una struttura del genere: Connessione -> DB -> Schema -> Tabella

Differenza tra Oracle e SQL Server

Oracle:

Connessione (es. Alias CRMSEADEV: tlyllt1b.sea.spa.dom, 1521) - DB (fa sempre parte della connessione, es. TLYLLT1B)- 
Schema (questo varia in base all'utenza, es. CRMOP, pw)
-> Tabella (es. ANAGRAFICA_CLIENTE)

SQL Server:

Connessione (es. sql.indicom.local. utenza es. matteo.aiello)
-> DB (es. Cust_Edenred)
  -> Schema (es. dbo) - Tabella (es. EDENRED_DOCS)



```


Versionamenti


```

Queste sono le versioni principali di SQL Server

2025  v17.0	
2022  v16.0	
2019  v15.0	
2017  v14.0	-- io ho questa in LV2


e invece queste sono le versioni x ssms (riceve aggiornamenti praticamente ogni anno)

2026 (Attuale)  v21.x		
2024-2025	      v20.x	
2022-2023       v19.x		-- io ho questa in LV2
2019-2022       v18.x		

test






```


Regole chiave per un corretto controllo


```

if (not exists (select * from tabella))
  eseguo l'insert
  select 'insert eseguito'
else
  select 'esiste già'

select * from tabella





```



