# 2021-5Ainf-esame-di-stato
Progetto di gruppo esame di stato



# Obiettivo
Realizzare una rete per un ospedale che ha 6 reparti su 3 piani, (ogni reparto si sviluppa su un unico piano) e vuole innovare la sua infrastruttura tecnologica per realizzare servizi interni. Una delle procedure da informatizzare riguarda la gestione delle terapie mediche prescritte giornalmente ai pazienti ricoverati. In particolare, si vuole che ogni medico di reparto, dopo avere visitato un paziente, possa collegarsi in modalita wireless ad un web server interno, dislocato in un locale tecnito, per registrare le seguenti informazioni.

# Progetto

https://prnt.sc/11pqcll


# Ipotesi aggiuntive: 
1) Ogni reparto puo avere piu di una stanza, quindi utilizzeremo il wifi controller per la rete per avere maggior velocita in tutto l'ospedale.
2) I medici e gli amministratori di rete avranno 2 tipologie di account separati per gestire nel miglior modo il paziente. Solo l' admin di rete può creare gli account e  sarà l'unico che potrà gestirli.
4) Non ci è stata richiesta della separazione della rete,quindi si preferisce utilizzare degli access point con la stessa sottorete.
5) L'edificio è stato appena costruito ed è di medie dimensioni.
6) Si tratta di una sola costruzione quindi si usera un solo CD/BD con un FD per piano CD= campus distributor, cioè distributore di insedimento , dove si concentrano le apparecchiature di distrubuzione di tutto l'impianto BD = Building distributor , cioè distributore di edificio , dove si concentrano le apparecchiature di distribuzione del singolo edificio. FD = è il floor distributor, cioè il distributore di piano
7) Per garantire una connessione efficente, si utilizzeranno i cavi Cat. 7A (FTP), frequenza: 1-1000 MHz, norma: EN 50288-9-1, Classe ISO 11801: Classe Fa, metri: 100, prezzo: 7,64 euro,  link: https://www.amazon.it/UGREEN-Ethernet-Console-Videogiochi-Compatibile/dp/B00QV1F1NS/ref=sr_1_3_sspa?dchild=1&keywords=cavo+ethernet+cat+7&qid=1618909565&sr=8-3-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUFKTUVBUDAwMEwxQTImZW5jcnlwdGVkSWQ9QTA0MTU3MDYyRDFKTU9MRE84Q1dPJmVuY3J5cHRlZEFkSWQ9QTA2NTQwNDQyVUdXRkxRU0dOT0VLJndpZGdldE5hbWU9c3BfYXRmJmFjdGlvbj1jbGlja1JlZGlyZWN0JmRvTm90TG9nQ2xpY2s9dHJ1ZQ==
8) Come inidizzo di rete si utilizzera l' indirizzo in classe A (10.0.0.0 con subnet 255.0.0.0) per garantire un aumento di dispositivi per utilizzi futuri.
