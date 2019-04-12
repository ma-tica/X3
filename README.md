# Sage X3 Tips & Tricks


Programmi:

-----------------------------------------------------------------
YALLOCOP

Permette l'allocazione disallocazione di un ordine di produzione

Parametri:
1. PMFGNUM -> Numero ordine di produzione
2. PALLOC  -> 1=Alloca, 0=Disalloca
3. WRET    -> Riferimento di ritorno, 0=OK

-----------------------------------------------------------------
YWSMAT

Permette il consumo di componenti

Parametri:
1. PMFGFCY  -> Sito di produzione
2. PMFGNUM  -> Ordine di produzione
3. PA_CMPITM -> (Array) Codice articolo componente
4. PA_CMPQTY -> (Array) Quantita' consumata
5. PA_CMPSTA -> (Array) Stato qualita del componente
6. PA_CMPLOC -> (Array) Ubicazione di prelievo
7. PA_CMPLOT -> (Array) Lotto componente
8. PA_CLEFLG -> (Array) Stato per saldare la riga del componente

Parametri di ritorno:
1. WY_MSGERR -> Messaggio di errore
2. WY_MFGTRKNUM -> Numero del tracking di avanzamento
