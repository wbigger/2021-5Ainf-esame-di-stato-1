# 2021-5Ainf-esame-di-stato
Progetto di gruppo esame di stato



# Obiettivo
Realizzare una rete per un ospedale che ha 6 reparti su 3 piani, (ogni reparto si sviluppa su un unico piano) e vuole innovare la sua infrastruttura tecnologica per realizzare servizi interni. Una delle procedure da informatizzare riguarda la gestione delle terapie mediche prescritte giornalmente ai pazienti ricoverati. In particolare, si vuole che ogni medico di reparto, dopo avere visitato un paziente, possa collegarsi in modalita wireless ad un web server interno, dislocato in un locale tecnito, per registrare le seguenti informazioni.


# Ipotesi aggiuntive: 

1) I medici e gli amministratori di rete avranno 2 tipologie di account separati per gestire nel miglior modo il paziente. Solo l' admin di rete può creare gli account e  sarà l'unico che potrà gestirli.
2) Non ci è stata richiesta della separazione della rete,quindi si preferisce utilizzare degli access point con la stessa sottorete.
3) L'edificio è stato appena costruito ed è di medie dimensioni.
4) Si tratta di una sola costruzione quindi si usera un solo CD/BD con un FD per piano
5) si iposizza che ogni reparto abbia un macchinario da connettere ad internet, quindi per ogni reparto ci sara una presa T/O
6) Come inidizzo di rete si utilizzera l' indirizzo in classe A (10.0.0.0 con subnet 255.0.0.0) per garantire un aumento di dispositivi per utilizzi futuri. Per ogni piano si utilizzera una subnet diversa.
7) Non ci e stato richiesto alcun tipo di dispositivo wireless per la farmacia, quindi si usera uno switch, collegato poi ad esso un pc.
8) Il protocollo web sara l' https con un web firewall (cloudfire)

# Abbreviazioni
## Presa T/O

Presa utente

## CD

CD = campus distributor, cioè distributore di insedimento , dove si concentrano le apparecchiature di distrubuzione di tutto l'impianto 

## BD

BD = Building distributor , cioè distributore di edificio , dove si concentrano le apparecchiature di distribuzione del singolo edificio.

## FD

FD = è il floor distributor, cioè il distributore di piano


# Progetto

[Packet Tracer](https://prnt.sc/11x3qhc) 

# Planimetrie
[Seminterrato](https://prnt.sc/11wxgvx) 

[Primo piano](https://prnt.sc/11wxeo2)

[Secondo piano](https://prnt.sc/11wxe3i)

[Terzo piano](https://prnt.sc/11wxd8v)

# Struttura dell' edificio 

[Struttura dell' edificio](https://prnt.sc/11wxt2w)

# Albero degli apparati passivi 

[Albero degli apparati passivi](https://prnt.sc/11wy6a7)

# Schema degli armadi

[Schema degli armadi](https://prnt.sc/11x3pij)

# Dispositivi

[Switch](https://www.amazon.it/TP-Link-TL-SG1048-Gigabit-Struttura-Acciaio/dp/B004UBUJZG) Abbiamo optato per 5 switch a 48 porte in vista di utilizzi futuri. Il costo e di: 196,64 € l' uno (196,64 * 5 = 983,2 euro)

[Access Point](https://www.amazon.it/Ubiquiti-Networks-UAP-AC-PRO-access-point/dp/B016XYQ3WK) Gli access point che si andranno ad utilizzare sono gli "Ubiquiti Networks" con protocollo "802.11.ac", la distanza massima di banda di questi dispositivi sono di 10 metri, e la velocita puo arrivare fino a 7gbps, il costo e di 155 euro l' uno (155 * 6 = 930 euro)

[Router](https://www.amazon.it/dp/B018WJTTG6?tag=tecnologiant-21&linkCode=osi&th=1&psc=1&keywords=router%20wi-fi%20AC) Il router che andremo ad utilizzare sara l' "Asus RT-AC88U", che supporta il protocollo 802.11.ac, Tecnologia Broadcom NitroQAMTM che supporta due data rate a 5 GHz fino a 2167 Mbps e uno a 2,4 GHz fino a 1000 Mbps. Il costo e di: 232 euro)

[Cavi fibra](https://www.amazon.it/UGREEN-Ethernet-Console-Videogiochi-Compatibile/dp/B00QV1F1NS) Per garantire una connessione efficente, si utilizzeranno i cavi Cat. 7A (FTP), frequenza: 1-1000 MHz, norma: EN 50288-9-1, Classe ISO 11801: Classe Fa, metri: 100, si useranno i cavi in fibra ottica perche una struttura ospedaliera ha anche molti macchinari nel reparto da connettere ad internet, quindi si e ipotizzato che la connessione dei macchinari e dei dispositivi devono essere sempre molto efficenti. Il costo e di: 7,64 euro

[Cavi rame](https://www.amazon.it/Mr-Tronic-metri-Ethernet-Grigio/dp/B07GBZ2S9J) Per collegare il pc della farmacia si utilizzera un cavo ethernet di tipo CAT 6a, di 5 metri, Classe EA 10GbEth, fino a 500 MHz. Il costo e di: 10,99 euro
