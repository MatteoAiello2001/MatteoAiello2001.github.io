```sql
/*<pre> 

*/
-- sql

-- Qua verranno messe tutte le info su SQL

-- x creare una nuova tabella

create table SafetyFepaCopy.dbo.InfoDoc (
  id int identity(1,1) primary key,
  codice varchar(255),
  idTipologieDocumentali int,
  idServizi int
)


ALTER TABLE [dbo].[_FE_FP_CompaniesDestinations] 
ADD CONSTRAINT [FK_CompaniesDestinations_PartnerCompanies] 
FOREIGN KEY ([entity_id]) REFERENCES [dbo].[_FE_FP_PartnerCompanies]([ID]);



SELECT 
  CASE 
    WHEN condizione1 THEN risultato1
    WHEN condizione2 THEN risultato2
    ELSE risultato_default
  END AS NomeColonna
FROM NomeTabella;




-- x fare una tabella

declare @lista varchar(255) = '05818530155, 03457730962, 02778640967, 10796040961, 10960910965, 07819360152, 05355951004, 06946631006, 10420860966, 11689160965, 11689250964, 11689210968, 11689290960, 07958400967, 10531600962, 11670440962, 10500140966, 02064260900, 10796050960, 12608980962, 07267741002, 13520860969, 05203500821, 10010841004, 02951740964, 13005260966, 06484610966, 14032600968, 14032610967, 14032620966, 14032630965, 14032660962, 14032690969, 14032670961, 14032680960'

select trim(value) from string_split(@lista, ',')



-- lo standard è questo x i db

/*
nome db         colonne o db
SQL Server      PascalCase o snake_case
Oracle          PascalCase o snake_case
MySQL           snake_case
*/


/*
```
</pre>
*/