# Activitat 3:
Per fer aquesta activitat comptem amb que **ja s'ha configurat el servei Owncloud a una Màquina Virtual** (MV).

**3.1.-** Llista els Virtual Hosts d'Apache per tal de veure si **owncloud.XYZ.com** està habilitat amb la comanda:

apache2ctl -S

**RESPOSTA**

![](Resposta1.png)

**3.2.-** A Owncloud podem veure que hi ha una serie de carpetes per defecte, mostra la ruta real a les tres carpetes dins de la teva MV.

**RESPOSTA**

![](FOTO3CARPETES.png)

**3.3.-** Al directori **Learn more about owncloud** hi ha informació en forma de fitxers pdf. Consulta'ls i respon aquestes preguntes:

- Quin són els tres tipus de protecció de dades que ofereix Owncloud?
- Fes una petita descripció de cada un d'ells.
- Per quina raó ens recomana utilitzar Owncloud per als documents de Microsoft Office de la nostra empresa?  
- Això passa a tots els països?
- Quina és la llicència d'OWncloud Enterprise?
- I la d'Owncloud Standard?
- Es poden veure videos en Streaming directament des de Owncloud?
- Es poden connectar directoris de Google Drive a Owncloud?
- I Dropbox?
- Compta Owncloud amb antivirus? En cas afirmatiu com es diu? 


1: Els tipus de protecció de dades que ofereix owncloud es: Cifratge de dades de caràcter personal, Integritat i resilliència de els sistemes, transparència i procediment i disponibilitat i accés.

2: CIFRATGE DE DADES DE CARÀCTER PERSONAL: Fà un xifratge d'extrem a extrem del costat del client, del costat del server amb ajuda del HSM
INTEGRITAT I RESILLIÈNCIA DELS SISTEMES: Es detecten els canvis en arxius inclus si son de una carga gran, ofereix autentificació de molts de factors, gestió de perfils, registre d'audiotoría, verificació d'integritat dels arxius, autentificació, clasificació i polítiques de documents.
DISPONIBILITAT I ACCÉS: Sempre està garantitzat ja que te protecció integrada contra ransomware.
TRANSPARÈNCIA I PROCEDIMENT: Owncloud ve amb un mmòdul d'auditoria/registra, una gestió d'autoritzacions transparent.
