# 2021-5Ainf-esame-di-stato
Progetto di gruppo esame di stato



# Obiettivo
Realizzare una rete per un ospedale che ha 6 reparti su 3 piani, (ogni reparto si sviluppa su un unico piano) e vuole innovare la sua infrastruttura tecnologica per realizzare servizi interni. Una delle procedure da informatizzare riguarda la gestione delle terapie mediche prescritte giornalmente ai pazienti ricoverati. In particolare, si vuole che ogni medico di reparto, dopo avere visitato un paziente, possa collegarsi in modalita wireless ad un web server interno, dislocato in un locale tecnito, per registrare le seguenti informazioni.


# Ipotesi aggiuntive: 
1) Ogni reparto puo avere piu di una stanza, quindi avremo bisogno di espansori di rete per avere maggior velocita in tutto l'ospedale.
2) I medici e gli infermieri avranno 2 account separati per gestire nel miglior modo il paziente ( esempio il medico potra modificare la cartella, l'infermiera protra solo leggerla senza modificare nulla/aggiungere, creando quindi una pagina web dove solo l'admin di rete puo registrare ogni medico/infermiere e dare loro le credenziali senza poter accedere, quindi facendo una regola outbound dove solamente l'admin di rete ha accesso a quella determinata pagina di login 
3) ipotizzando che la grandezza media di ogni reparto sia di di 100metri, ogni access point in genere ha di media 45 metri di banda, mettendo l access point all altrata del reparto avremmo bisogno di 2 espansori di rete ipotizzando che possa arrivare ad una lunghezza d'onda di circa 30 metri messi a 30 metri l'uno dall altro. 
