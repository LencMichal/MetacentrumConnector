# MetacentrumConnector
Easy connect to VNC sesion on metacentrum.
#####################################

N�sleduj�c� script slou�� ke spu�t�n� a p�ihl�en� do vzd�len� plochy Metacentra. 
Script se p�ihl�s� k uzlu Metacentra, spust� VNC sesion, vytvo�� SSL tunel na lok�ln�m PC a spust� klienta VNC v maximalizovan�m okn�. 

#####################################

Scipt se spou�t� dvojklikelm na soubor ClickMe.exe.
Stisknut�m "Ctrl+Shit+T" dojde k zah�jen� vykon�v�n� scriptu. 
P�i prvn�m spu�t�n� v�s vyzve k zad�n� u�ivatelsk�ho jm�na a hesla pro p��stup k Metacentru.
N�sledn� dojde k p�ihl�n� k uzlu metacentra, spu�t�n� grafick�ho u�ivatelsk�ho rozhran�, spu�t�n� VNC serveru. Z poskytnut�ch p�ihla�ovac�ch �daj� je spu�t�n SSL tunel a k n�mu p�ipojen VNC klient v PC. Klient je spu�t�n maximalizovan�.
P�i zav�en� okna VNC klienta nedojde k ukon�en� VNC sesion. Ke spu�t�n� vzd�len� plo�e s rozd�lanou prac� je mo�n� se znovu p�ipojit spu�t�n�m souboru VzdalenaPlocha.vnc 
(Mus� st�le b�et Stunnel v tray li�t� a p��pona soubory typu .vnc mus� b�t p�i�azeny VNC vieweru.)

#####################################

Jak nastavit VNC viewer jako v�choz� aplikaci pro spou�t�n� soubor� .vnc?

Prav�m tla��tkem na soubor VzdalenaPlocha.vnc -> Otev��t v Programu -> Zvolit v�choz� program
(Za�krtnout "K otev�en� soubor� tohoto typu v�dy pou��t vybran� program")
-> Proch�zet -> slo�ka MetacentrumVNC\Windows\util\vncviewer.exe
T�mto dojde k p�i�azen� soubor� (p��pony) .vnc k programu vncviewer, kter� slou�� jako VNC klient. 

#####################################

P��padn� dotazy m��ete sm��ovat p��mo na michal.lenc@gmail.com, 
nebo m� kontaktovat p�e Michaela Tesa�e. 
Script bude pr�b�ne aktualizov�n a zlep�ov�n. Pokud se stane aktivn�mi u�ivateli, ozv�te se mi pros�m na michal.lenc@gmail.com, budu v�s pr�b�ne informovat o novink�ch. 