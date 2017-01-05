# MetacentrumConnector
Easy connect to VNC sesion on metacentrum.
#####################################

Následující script slouží ke spuštìní a pøihlášení do vzdálené plochy Metacentra. 
Script se pøihlásí k uzlu Metacentra, spustí VNC sesion, vytvoøí SSL tunel na lokálním PC a spustí klienta VNC v maximalizovaném oknì. 

#####################################

Scipt se spouští dvojklikelm na soubor ClickMe.exe.
Stisknutím "Ctrl+Shit+T" dojde k zahájení vykonávání scriptu. 
Pøi prvním spuštìní vás vyzve k zadání uživatelského jména a hesla pro pøístup k Metacentru.
Následnì dojde k pøihlášní k uzlu metacentra, spuštìní grafického uživatelského rozhraní, spuštìní VNC serveru. Z poskytnutých pøihlašovacích údajù je spuštìn SSL tunel a k nìmu pøipojen VNC klient v PC. Klient je spuštìn maximalizovaný.
Pøi zavøení okna VNC klienta nedojde k ukonèení VNC sesion. Ke spuštìné vzdálené ploše s rozdìlanou prací je možné se znovu pøipojit spuštìním souboru VzdalenaPlocha.vnc 
(Musí stále bìžet Stunnel v tray lištì a pøípona soubory typu .vnc musí být pøiøazeny VNC vieweru.)

#####################################

Jak nastavit VNC viewer jako výchozí aplikaci pro spouštìní souborù .vnc?

Pravým tlaèítkem na soubor VzdalenaPlocha.vnc -> Otevøít v Programu -> Zvolit výchozí program
(Zaškrtnout "K otevøení souborù tohoto typu vždy použít vybraný program")
-> Procházet -> složka MetacentrumVNC\Windows\util\vncviewer.exe
Tímto dojde k pøiøazení souborù (pøípony) .vnc k programu vncviewer, který slouží jako VNC klient. 

#####################################

Pøípadné dotazy mùžete smìøovat pøímo na michal.lenc@gmail.com, 
nebo mì kontaktovat pøe Michaela Tesaøe. 
Script bude prùbìžne aktualizován a zlepšován. Pokud se stane aktivními uživateli, ozvìte se mi prosím na michal.lenc@gmail.com, budu vás prùbìžne informovat o novinkách. 