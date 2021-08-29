# Homematic Steuerung für drei 12V Dachfensterjalousieantriebe
 
 Eine Steuerung mit drei Polwendern für 12Volt Gleichstromantriebe basierend auf der Asksin++ Bibliothek von <a href="http://https://github.com/pa-pa/AskSinPP">pa-pa</a>.
 
 Ursprünglich hatten die Dachfensterjalousien eine Funksteuerung mit Akkus und Solarzellen.<br>
 Da der Wunsch bestand, die Antriebe über die Homematicsteuerung fahren zu können, wurde eine Steuerung entworfen und die Antriebsmotore direkt per Kabel an diese angeschlossen.<br>
 In FHEM oder Rasperrymatic/CCU3 wird das Modul als HM-MOD-RE-8 erkannt. Es werden aber nur die ersten 6 von 8 Kanälen benutzt.<br>
 Die Platine (160mmx100mm) wurde mit KiCad erstellt und in China gefertigt.<br>
 <br>
 Geflasht wird der Arduino Pro Mini mit der Arduino-IDE<br>
 <br>
 Benötigte Hardware<br>
-1x Arduino Pro Mini ATmega328P (3.3V/8MHz)<br>
-1x CC1101 Funkmodul (868 MHz)<br>
-1x Trafo 230V/12V, 50VA, diverse Kleinteile (z.B. von Reichelt -  <a href="https://www.reichelt.de/my/1860438">Warenkorb</a>).<br>
-Gehäuse / Verschraubungen (z.B. von Amazon)<br>
-FTDI Adapter (wird nur zum Flashen benötigt)<br>

![20210511_200453 (2)](https://user-images.githubusercontent.com/54813823/121245362-3be33280-c8a0-11eb-8381-da3ecbc8c681.jpg)
![20210511_200513 (2)](https://user-images.githubusercontent.com/54813823/121245381-41d91380-c8a0-11eb-9043-20dd7400ecaf.jpg)
![20210512_123509 (2)](https://user-images.githubusercontent.com/54813823/121245059-e149d680-c89f-11eb-8447-cdb9724a8054.jpg)
