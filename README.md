# fritzbox-WAN-guide-german
### Wie bekomme ich Internet im Wohnheim mit meiner FritzBox!?

**! wichtiger allgemeiner Hinweis!:** Wenn man vorher ein anderes Gerät an dem Anschluss des Studierendenwerks benutzt hat(Computer oder Router) muss der Anschluss von dem/der Netztutor/Netztutorin erst wieder zurück gesetzt werden(mit ausgestecktem LAN-Kabel an der Wand) bevor man ein anderes Gerät konfigurieren kann.\
<br/>


### Erfahrungsbericht FRITZ!Box 7490(andere Geräte sollten ähnlich funktionieren) Internetfreischaltung stand 04.2021 unter FRITZ!OS 7.21 (super ausführlich) erweitert am 10.2021:

**!sehr wichtiger Hinweis!: Bitte vor und während dem konfigurieren die FRITZ!Box von der LAN-Buchse getrennt halten(die ersten fünf Schritte)! Da die FRITZ!Box während der Konfiguration das Netz stören kann und der Anschluss dadurch gesperrt wird und dann erst wieder von dem/der Netztutor/Netztutorin zurück gesetzt werden muss(mit ausgestecktem LAN-Kabel).**

0. Box auf Werkeinstellungen zurück setzen(erübrigt sich bei einem neuem Gerät). Und dich mit der internen VO-Nummer(steht auf deinem Mietvertrag) bei den Netztutor*innen melden. Die Email steht auf einem der Dokumente, die du von dem Studierendenwerk bekommen hast und warten bis jemand deinen Anschluss freigeschaltet hat.
1. Computer mit der Fritzbox verbinden(LAN Kabel in einen LAN Slot der FRITZ!Box stecken, **LAN1-Slot vorsichtshalber frei lassen!**) oder über W-Lan(Name: FRITZ!Box 7490) mit dem Netzwerkschlüssel, der hinten auf dem Gerät steht, als Passwort verbinden. Nachfolgend in dem Browser(z.B. Mozilla Firefox) "fritz.box" ohne die Anführungszeichen in die Adresszeile tippen, bestätigen, und so die Administrations-Seite aufrufen.
2. ein sicheres Passwort für die FRITZ!Box-Administrationsoberfläche festlegen.
3. auf "Einstellungen übernehmen"(im Text) klicken, um den Einrichtungsassistenten zu beenden.
4. oben Rechts(über dem Fragezeichen) auf die drei Punkte klicken und die Erweiterte Ansicht einschalten.(**Hinweis!:** bei manchen Geräten gibt es diese Auswahlmöglichkeit nicht, dann ganz normal weiter)
5. unter Internet>Zugangsdaten(links in dem Menü) unter Internetzugang(Reitermenü) folgende Einstellungen vornehmen ->\
**Internetanbieter**: weitere Internetanbieter, andere Internetanbieter\
**Anschluss**: Anschluss an externes Modem oder Router\
**Betriebsart**: Internetverbindung selbst aufbauen\
**Zugangsdaten**: Nein\
**Verbindungseinstellungen**: Down- und Upstream auf Standarteinstellungen lassen\
Auf das blau hinterlegte "Verbindungseinstellungen ändern"(steht direkt darunter) klicken und "IP-Adresse manuell festlegen" auswählen.\
Dort die IP-, Subnet-, Gateway-, DNS1- , DNS2- Adresse, die du von dem/der Netztutor/Netztutorin erhalten hast bitte korrekt eintragen. Nochmal überprüfen, ob man die Adressen wirklich korrekt abgetippt hat(gibt später sonst Probleme) und auf "Übernehmen" klicken. Eventuell muss man die Eingabe mit einem Knopfdruck auf eine der Tasten der FRITZ!Box bestätigen.
Die Einstellungen werden geändert. Unter Umständen wird noch die Verbindung getestet. Das abwarten. Es wird fehlschlagen(keine Sorge).
6. das **LAN-Kabel** mit dem **WAN-Anschluss**(bei den meisten FRITZ!Boxen(z.B. 7490) liegt dieser Anschluss auf dem LAN1 Anschluss → d.h. im zweiten Fall muss das Kabel in den **LAN1 Anschluss** gesteckt werden!) der Fritzbox verbinden und das andere Ende in die LAN Buchse in der Wand stecken. (**!sehr wichtiger Hinweis!:** bei der FRITZ!Box 4020 gibt es z.B. eine separate blaue WAN-Buchse, in diesem Fall steckt man das LAN-Kabel in diese blaue WAN-Buchse und der LAN1-Anschluss kann ganz normal verwendet werden)
7. links in dem Menü unter System>Update unter FRITZ!OS-Version(Reitermenü) auf "neues FRITZ!OS suchen" klicken und eventuell installieren(dauert etwas). Die FRITZ!Box wird anschließend neu gestartet und man muss sich nochmal an der Administrationsoberfläche anmelden.(während dem Update hat man kein Internet)
8. im Menü unter System>Update unter Auto-Update(Reitermenü)
"Stufe III: Über neue FRITZ!OS-Versionen informieren und neue Versionen automatisch installieren (Empfohlen)" auswählen, falls es noch nicht ausgewählt ist und auf "Übernehmen" klicken.\
**!Hinweis des Herstellers!:**\
Andere FRITZ!-Produkte im WLAN Mesh übernehmen automatisch diese Einstellungen von der FRITZ!Box.
Achten Sie darauf, dass Updates auf Ihren Geräten je nach Einstellung automatisch starten können und Sie in dieser Zeit die Stromversorgung der Geräte nicht unterbrechen dürfen. Ein laufendes Update können Sie anhand einer blinkenden Info- oder Power-LED erkennen.
Während der Installation werden die Internet- und Telefonieverbindungen kurzzeitig unterbrochen.

9. im Menü unter WLAN>Funknetz unter Funknetz-Name(Reitermenü) einen eigenen Namen für dein W-LAN festlegen und sicher gehen dass "Name des WLAN-Funknetzes sichtbar" ausgewählt ist.
10. im Menü unter WLAN>Sicherheit unter WPA-Verschlüsselung(Reitermenü) "WPA2 + WPA3" auswählen. In neueren Versionen kann es sein, dass man nur "WPA3" auswählen kann, diese Einstellung sollte man dann beibehalten. Bei Bedarf kann im selben Fenster noch der WLAN-Netzwerkschlüssel(Passwort für das WLAN) geändert werden. Der Netzwerkschlüssel, der hinten auf dem Router steht ist sicher, kann aber für alle Leute, die Zugang zu dem Router haben, eingesehen werden.

Bei Bedarf:
11. im Menü unter System>Tasten und LEDs unter LED-Anzeige kann man die LED-Anzeige ausschalten("LED-Anzeige ausschalten" auswählen). Das spart etwas Strom und man hat nachts nicht die Lichtbelastung durch die LEDs.\
**!Hinweis des Herstellers!:**\
Bei Tastendruck, wichtigen Ereignissen und Neustart der FRITZ!Box werden mit den LEDs Statusinformationen weiterhin angezeigt. (D.h. bei einem automatischen Update blinken die LEDs trotzdem noch, oder wenn es Probleme mit dem Internet gibt, leuchtet die DSL-LED rot)

12. Geschafft! Los surfen und viel Spaß!
