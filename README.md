# Sage X3 Tips & Tricks


Programmi:

-----------------------------------------------------------------
YALLOCOP

Permette l'allocazione disallocazione di un ordine di produzione

Parametri:
PMFGNUM -> Numero ordine di produzione
PALLOC  -> 1=Alloca, 0=Disalloca
WRET    -> Riferimento di ritorno, 0=OK

-----------------------------------------------------------------
YWSMAT

Permette il consumo di componenti

Parametri:
PMFGFCY  -> Sito di produzione
PMFGNUM  -> Ordine di produzione
PA_CMPITM -> (Array) Codice articolo componente
PA_CMPQTY -> (Array) Quantita' consumata
PA_CMPSTA -> (Array) Stato qualita del componente
PA_CMPLOC -> (Array) Ubicazione di prelievo
PA_CMPLOT -> (Array) Lotto componente
PA_CLEFLG -> (Array) Stato per saldare la riga del componente

Parametri di ritorno:
WY_MSGERR -> Messaggio di errore
WY_MFGTRKNUM -> Numero del tracking di avanzamento
