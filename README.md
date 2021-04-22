# 2021-5Ainf-esame-di-stato
Progetto di gruppo esame di stato



# Obiettivo
Realizzare una rete per un ospedale che ha 6 reparti su 3 piani, (ogni reparto si sviluppa su un unico piano) e vuole innovare la sua infrastruttura tecnologica per realizzare servizi interni. Una delle procedure da informatizzare riguarda la gestione delle terapie mediche prescritte giornalmente ai pazienti ricoverati. In particolare, si vuole che ogni medico di reparto, dopo avere visitato un paziente, possa collegarsi in modalita wireless ad un web server interno, dislocato in un locale tecnito, per registrare le seguenti informazioni.

# Progetto

[Packet Tracer](https://prnt.sc/11usahl) 

# Planimetrie
[Seminterrato](https://prnt.sc/11v47en) 

[Primo piano](https://prnt.sc/11v4agw)

[Secondo piano]()

[Terzo piano]()

# Dispositivi

[Switch](https://www.amazon.it/TP-Link-TL-SG1048-Gigabit-Struttura-Acciaio/dp/B004UBUJZG) Abbiamo optato per 4 switch a 48 porte in vista di utilizzi futuri

[Access Point](https://www.amazon.it/Ubiquiti-Networks-UAP-AC-PRO-access-point/dp/B016XYQ3WK) Gli access point che si andranno ad utilizzare sono gli "Ubiquiti Networks" con protocollo "802.11.ac", la distanza massima di banda di questi dispositivi sono di 10 metri, e la velocita puo arrivare fino a 7gbps, il costo e di 155 euro (155* 6 = 930 euro)

[Router](https://www.amazon.it/dp/B018WJTTG6?tag=tecnologiant-21&linkCode=osi&th=1&psc=1&keywords=router%20wi-fi%20AC) Il router che andremo ad utilizzare sara l' "Asus RT-AC88U", che supporta il protocollo 802.11.ac, Tecnologia Broadcom NitroQAMTM che supporta due data rate a 5 GHz fino a 2167 Mbps e uno a 2,4 GHz fino a 1000 Mbps. Costo= 232 euro)

# Ipotesi aggiuntive: 
1) Ogni reparto puo avere piu di una stanza, quindi utilizzeremo il wifi controller per la rete per avere maggior velocita in tutto l'ospedale.
2) I medici e gli amministratori di rete avranno 2 tipologie di account separati per gestire nel miglior modo il paziente. Solo l' admin di rete può creare gli account e  sarà l'unico che potrà gestirli.
4) Non ci è stata richiesta della separazione della rete,quindi si preferisce utilizzare degli access point con la stessa sottorete.
5) L'edificio è stato appena costruito ed è di medie dimensioni.
6) Si tratta di una sola costruzione quindi si usera un solo CD/BD con un FD per piano CD= campus distributor, cioè distributore di insedimento , dove si concentrano le apparecchiature di distrubuzione di tutto l'impianto BD = Building distributor , cioè distributore di edificio , dove si concentrano le apparecchiature di distribuzione del singolo edificio. FD = è il floor distributor, cioè il distributore di piano
7) Per garantire una connessione efficente, si utilizzeranno i cavi Cat. 7A (FTP), frequenza: 1-1000 MHz, norma: EN 50288-9-1, Classe ISO 11801: Classe Fa, metri: 100, prezzo: 7,64 euro, si useranno i cavi in fibra ottica perche una struttura ospedaliera ha anche molti macchinari nel reparto da connettere ad internet, quindi si e ipotizzato che la connessione dei macchinari e dei dispositivi devono essere sempre molto efficenti
[link](https://www.amazon.it/UGREEN-Ethernet-Console-Videogiochi-Compatibile/dp/B00QV1F1NS)
8) Come inidizzo di rete si utilizzera l' indirizzo in classe A (10.0.0.0 con subnet 255.0.0.0) per garantire un aumento di dispositivi per utilizzi futuri. Per ogni reparto si utilizzera una subnet diversa.
9) Non ci e stato richiesto alcun tipo di dispositivo wireless per la farmacia, quindi si usera uno switch, collegato poi ad esso un pc.
