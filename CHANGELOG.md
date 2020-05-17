## Version 3.0.0-84, _17.05.2020_

Dies ist das letzte Release des sBinders! Es gibt den sBinder jetzt seit über acht Jahren, also länger als Newlife. Ich hab damit angefangen als ich 13 war. Auf Nova war ich schon seit über 5 Jahren nicht mehr aktiv, trotzdem gab es für den sBinder immer mal wieder Updates (wenn auch halbherzig; das letzte ist schon wieder über ein Jahr her). Und funktionieren tut er heute noch. Jetzt ist aber Zeit für einen Schlussstrich, daher ist das das vorerst letzte Update. Den Server im Hintergrund, der Sachen wie `/playerinfo` ermöglicht, lasse ich erstmal online, der läuft die meiste Zeit ohne große Probleme vor sich hin. Wenn dort Probleme auftreten sollten kann ich aber nicht versprechen dass diese gefixt werden, melden könnt ihr mir das trotzdem.

Dafür ist der sBinder jetzt aber auch [Open Source auf GitHub](https://github.com/MarcelGerber/sBinder), wer will kann also den Code für eigene Zwecke nutzen, selbst Anpassungen vornehmen oder was auch immer.

Danke euch allen für die treuen Jahre, für zeitweise über 200 aktive Nutzer und viel Spaß auch weiterhin!

Und jetzt zu dem was neu ist in diesem letzten Update:

- Es werden keine Fraktionspasswörter mehr benötigt!
- Die Befehle `/music`, `/youtube`, `/radio` sowie `/wolframalpha` wurden entfernt
- Neue Fraktionsnamen
- Update des Wantedkatalogs
- Es werden keine Trucking-EP mehr hochgeladen
- Die LCN hat keine `/sg`-Befehle mehr

## Version 2.4.0-83, _21.03.2019_

- Unterstützung für die Fraktionen Ndrangheta und San Andreas Army Corps bei /checkfrak, /playerinfo etc.
- Timer für /use lsd/green/gold/donut werden nur (neu) gestartet, wenn die Substanz wirklich eingenommen wurde
- Aktualisierung des Wantedkatalogs (s. Forum)
- /znotiz all funktioniert auch mit aktivierter API wieder
- /fucku von den /me-Texten entfernt (wird von der Bundeswehr zum Salutieren genutzt)

#### Nachträglich (Build 83.1)

- Bei /use lsd etc. werden Verzögerungen in der Abarbeitung der Binds vermieden

## Version 2.3.2-82, _23.11.2018_

- Im Overlay kann auch [LsdTimer], [GreenTimer], [DonutTimer] und [GoldTimer] verwendet werden, die jeweils die Zeit bis zum nächsten /use anzeigen (Green, Donut und Gold zeigen dabei immer die gleiche Zeit). Bei LSD wird zusätzlich die Zeit bis zur Nebenwirkung angezeigt
- Update des Fahrzeugrechners: Neu ist das Prestige Autohaus in San Fierro, außerdem sind die Preise für Panzerung korrekt
- Aktualisierung des Wantedkatalogs: Neu ist /itätigkeit (Illegale Ausübung einer genehmigungspflichtigen Tätigkeit)

## Version 2.3.1-81, _21.10.2018_

- Bei "/use [lsd/green/donut/gold]" wird ein Timer gestartet, der euch benachrichtigt, wann ihr die nächste Dosis einnehmen könnt. Bei LSD werdet ihr zusätzlich kurz vor den Nebenwirkugen gewarnt (kann in den Einstellungen deaktiviert werden)
- Auf HiDPI-Displays wird das GUI korrekt angezeigt
- Anpassung des Wantedkatalogs: Werben für illegale Aktivitäten/Produkte -> 20 WP
- Eigene Binds mit /use-Befehlen funktionieren wieder

## Version 2.3.0-80, _25.09.2018_

- Der sBinder sollte von deutlich weniger Antivirenprogrammen als schädlich erkannt werden; dafür ist die .exe-Datei etwas größer geworden
- Der Fahrzeugrechner wurde aktualisiert: Insbesondere wurde das El Corrona Autohaus mit Fahrzeugen hinzugefügt sowie weitere Panzerungsstufen
- Der sBinder muss nicht mehr zwingend mit Adminrechten gestartet werden: Wird der Systemdialog verneint, so kann der sBinder dennoch genutzt werden; in den Erweiterten Optionen gibt es zusätzlich eine Option, sodass der Dialog komplett deaktiviert wird (dennoch nicht empfohlen)
- Wird der sBinder mithilfe der Entf-Taste oder /kstop deaktiviert, so werden auch alle Overlays ausgeblendet
- Der Name des GTA-Prozesses kann eingestellt werden, sodass der sBinder auch bei einer umbenannten gta_sa.exe funktioniert

## Version 2.2.1-79, _04.09.2018_

- Anpassungen an den Wantedkatalog:
  - Geändert: /kv – Körperverletzung: 15 WPs
  - Neu: /bsg – Beschuss im Sperrgebiet, /drogen1, /drogen2, /drogen3 je nach Menge, /waffenhandel2 – Illegaler Waffenhandel ohne Lizenz, /anschlag – Anschlag auf ein Staatsoberhaupt, /lsflug – Landen/Starten auf öffentl. Straßen
  - Entfernt: /shetze, /shetzew – Hetze gegen den Staat, /aufenthalt – Illegaler Aufenthalt in SF/Bayside, /pstörung – Prüfungsstörung
- Es gibt wieder /kpd (/kpayday), um bei einem Payday automatisch die beiden Zahlen zu addieren
- /wpbinds zeigt auch mit aktivierter API bloß eine Liste im Chat an

## Version 2.2.0-78, _23.07.2018_

- Der sBinder funktioniert jetzt mit einer von [NeS]shoXy abgeänderten API, die mit dem Anti-Cheat System kompatibel ist!
- Unter Einstellungen > Overlay-Einstellungen (neben der API) könnt ihr ein Overlay aktivieren, das viele Konfigurationsmöglichkeiten hat (Schriftart, -größe, Position, Farbe, Text) und auch im Text gibt es Möglichkeiten wie [Heal], [FPS], [Time] usw.

## Version 2.1.8-77, _21.03.2018_

- Das Shanghai Syndikat wurde zu Triaden umbenannt und funktioniert auch bei /checkfrak und /playerinfo wieder
- Alle veralteten Shanghai Syndikat bzw. Medellin Kartell Binds wurden entfernt

## Version 2.1.7-76, _24.02.2018_

- Eigene Textbinds sollten jetzt in der Funktionalität kaum mehr von den eingebauten Textbinds zu unterscheiden sein
- Der WP-Bind Körperverletzung (/kv) vergibt 15 WPs

## Version 2.1.6-75, _22.12.2017_

- /checkfrak geht nun auch für das Shanghai Syndikat

## Version 2.1.5-74, _07.08.2017_

- Kompatibilität mit dem AntiCheat-System
- Neue Fahrzeuge im Fahrzeugrechner
- Chat-Mitteilung beim SARD-Befehl /drop medikamente

## Version 2.1.4-73, _02.01.2017_

- Neue Fraktion: Medellin Kartell

## Version 2.1.3-72, _14.12.2016_

- Medellin Kartell bei /checkfrak usw.
- Neuer Fraktionsbind fürs Police Department

## Version 2.1.2-71, _26.11.2016_

- Das System zum Chat-Auslesen wurde deutlich verbessert
- Fehler im Updatesystem behoben
- /car lock [Nummer] wurde auf bis zu 20 erhöht
- /kfish und /ksell entfernt

## Version 2.1.1-70, _22.11.2016_

- Alle Preise im Fahrzeugrechner angepasst
- Anpassungen an den neuen Wantedkatalog (s. /wpbinds)
- Es werden keine Daten mehr ans SARD-Interface gesendet

## Version 2.1.0-69, _17.10.2016_

- Generelle Anpassung der Jobs an NewLife, inklusive vielen neuen Jobs
- Neue Fraktion: Varrios Los Aztecas
- Beim Auslesen des Chats kommt es zu weniger Fehlern
- Einige Anpassungen bei den SARD-Binds
- Entfernen von /kpayday
- /use herbs wurde aus den Fraktionsbinds entfernt

#### Nachträglich (Build 69.1)

- Anpassungen bei einigen SARD-Binds
- Drogensystem der Grove Street entfernt

## Version 2.0.10-68, _06.10.2016_

- Beim SA:RD stehen zwei weitere Funkrufnummern zur Vefügung, sodass es nun insgesamt 5 gibt
- Beim /accept medic-Bind wird der erste Auftrag im Dialog automatisch ausgewählt
- Bei /mpdelete wird eine Meldung in den /r-Chat geschrieben

#### Nachträglich (Build 68.1)

- PD-Bind Traffic Stop gefixt
- Beim /accept medic-Bind muss der Auftrag nun wieder manuell ausgewählt werden

#### Nachträglich (Build 68.2)

- Für /mpdrop wird die neue Meldung ausgelesen

## Version 2.0.9-67, _11.09.2016_

- Rebellen stehen bei /checkfrak usw. nicht mehr zur Auswahl
- Überarbeitung der San Andreas Police Department-Fraktionsbinds

## Version 2.0.8-66, _09.09.2016_

- Problem im Updatevorgang behoben
- Rebellen und Varrios Los Aztecos bei /checkfrak usw.
- Entfernen eines SA:RD-Binds: /mv + /oldmv

## Version 2.0.7-65, _19.08.2016_

- Anpassungen an den neuen Wantedkatalog (s. /wpbinds)
- Neuer Bind für das SA:RD: Brandeinsatz angenommen -- Status 3

## Version 2.0.6-64, _05.04.2016_

- Anpassungen an den Wantedkatalog (s. /wpbinds)

## Version 2.0.5-63, _19.02.2016_

- Da der NSC nicht mehr benötigt wird, startet der Connect-Button wieder SAMP
- Anpassungen an den Wantedkatalog (s. /wpbinds): Neu: /craub, /üraub, /mittäter (/smordm); Geändert: /staatsgefährdung1 -> /staatsgefährdung
- /respekt an NewLife angepasst

## Version 2.0.4-62, _22.12.2015_

- Neue Fraktion: FBI
- O’Sullivan Mob und FBI bei /checkfrak usw.

## Version 2.0.3-61, _01.11.2015_

- Im SARD ist die Übermittlung von Daten ans SARD Interface nun standardmäßig deaktiviert, sie kann bei den Fraktionsbinds aktiviert werden
- Im LSPD wird mit Doppelhupe auch das Tor des Verwahrplatzes (/towopen) geöffnet

## Version 2.0.2-60, _10.10.2015_

- Entfernen einiger Fraktionen, die auf NewLife nicht mehr existieren (darunter auch die San Fierro Rifa)
- Entfernen von /übungen

## Version 2.0.1-59, _08.10.2015_

- Angepasste Fahrzeug-/Addonpreise im Fahrzeugrechner und bei /carvalue

## Version 2.0.0-58, _06.10.2015_

- Anpassungen an Nova-eSports NewLife

## Version 1.3.13-57, _26.07.2015_

- Anpassungen an den vorübergehenden Wantedkatalog (s. /wpbinds): Entfernt: /msmord

## Version 1.3.12-56, _14.07.2015_

- Anpassungen an den neuen Wantedkatalog (s. /wpbinds): Neu: /braub, /bsgen, /bhack, /ssperrgebiet (/ssg); Geändert: /sperrgebiet (/sg)
- Fahrzeugrechner: Andromada, Nevada und PCJ-600 hinzugefügt
- /use crowd -> /use herbs
- Button in den Einstellungen hinzugefügt, der die chatlog.txt automatisch sucht

## Version 1.3.11-55, _26.04.2015_

- Anpassungen an den neuen Wantedkatalog (s. /wpbinds): Neu: /msmord
- Die API ist nicht mehr standardmäßig aktiviert (betrifft nur neue Nutzer)
- Problem behoben, bei dem der Name nicht angezeigt wurde, wenn ein Design verwendet wurde
- Taxiteam: Ändern von "Am Taxistand" zu "In Bereitschaft"
- Ändern des /id-Binds der Hitmen
- Bugfix beim "/accept medic"-Bind des Rettungsdienstes

## Version 1.3.10-54, _06.04.2015_

- Neue Fraktion: Hitmen
- Taxiteam: Ändern von "In Bereitschaft" zu "Am Taxistand"

## Version 1.3.9-53, _13.03.2015_

- Anpassungen an den neuen Wantedkatalog (s. /wpbinds): /drogen30, /drogen31 → /drogen50, /drogen51, Neu: /shetze, /shetzew, /öffland, /öffstart
- Fahrzeugrechner: Versicherungspreis angepasst (8000\$, da man bis zu 10 kaufen kann), Cheetah hinzugefügt
- Entfernen aller Vorkommen von /use widow

## Version 1.3.8-52, _26.01.2015_

- Neue Fraktion: Korsakow Familie
- WP-Bind /raub -> /raubwp (Grund: Animation /raub)

## Version 1.3.7-51, _30.12.2014_

- Bei /playerinfo werden frühere Namen eines Spielers angezeigt
- Neue Fraktion: Los Vagos
- /checkfrak wp bzw. /membersonline wp gibt für jeden Spieler einer Fraktion, der online ist, /checkwanted ein
- Die Korsakow Familie wird von /checkfrak bzw. /membersonline, /membersall und /leaders unterstützt
- Bei /checkfrak bzw. /membersonline, /membersall und /leaders kann auch BFC eingegeben werden, um die Member der Blackfield Church anzuzeigen

## Version 1.3.6-50, _16.12.2014_

- Neuer Textbind: /myfrak
- Bessere Ingame-Darstellung von /membersall
- Überarbeitung der Dillimore Devils-Fraktionsbinds
- Verbesserungen beim LCN-Fraktionsbind /sg list
- Der LCN-Fraktionsbind /ssp geht wieder für alle Pizzen

## Version 1.3.5-49, _08.11.2014_

- Trucker Top 50: Anzeige der aktuellen Ranglisten-Position
- Daten wie Fraktionspasswörter werden gecacht, sodass sie auch ohne Internetverbindung bzw. bei Serverproblemen noch genutzt werden können
- Standardmäßig wird beim ersten Start die zuletzt geänderte chatlog.txt gesucht und genutzt, falls es mehrere gibt. Das sollte etwaige Probleme beim Auslesen des Chats beheben
- Caching von Online-Daten deaktiviert
- Anpassungen an den neuen Wantedkatalog (s. /wpbinds). Neu: /sdiebstahl, /raub
- O-Amt: /accept mechaniker als Fraktionsbind

## Version 1.3.4-48, _14.09.2014_

- Neues Design: "Graphite" - dunkel und kompakt
- Bei /echo werden mehr Zeichen pro Zeile gesendet -> weniger Umbrüche
- "Ordnungsamt" bei /membersonline/checkfrak/leaders zeigt nicht mehr die SAM AG

## Version 1.3.3-47, _03.09.2014_

- NSC-Support: Option "NSC starten" startet NSC und verbindet mit dem Server
- Fahrzeugrechner + /carvalue: Xoomer Autohaus hinzugefügt, Anpassungen bei den Carheal-Preisen [[Quelle](http://forum.nes-reallife.de/index.php/Thread/177988-Carheal-Wertboom/)]
- Blackfield Church und O’Sullivan Mob bei /membersonline (/checkfrak), /leaders usw.
- Anpassungen an den neuen Wantedkatalog (s. /wpbinds). Neu: /dicewp, /drogentransport (/dtrans), Entfernt: /drogenfahrt
- PD, FBI, Army: /me funkt zur Zentrale als Fraktionsbind
- SAM AG: /breaklive als Fraktionsbind
- Der SA:RD kann eine 3. FRN nutzen
- O-Amt: /tt und /ttlist funktionieren wieder
- GS: /plants und /fpkeep funktionieren wieder
- LCN: /sg und /ml funktionieren wieder

## Version 1.3.2-46, _18.04.2014_

- Scarfo -> San Fierro Rifa
- Update des Fahrzeugrechners + /carvalue (Kofferraum hinzugefügt, Schlosspreis = ¼×Fahrzeugwert)
- Medics können zwischen zwei verschiedenen Funkrufnummern wählen (z.B. für Medicopter). Außerdem wird bei /mpdrop eine Meldung in den /r-Chat gesendet.
- Es gibt die Möglichkeit, die Trucker-Erfahrungspunkte automatisch in die Trucker Top 50 eintragen zu lassen (muss in den Einstellungen aktiviert werden)
- Der neue /echo-"Chat" wird genutzt, um Daten an euch auszugeben. Das sieht kein anderer.
- Neuer Textbind: /wolframalpha

#### Nachträglich (Build 46.1)

- Automatischer Upload der Trucker-Erfahrungspunkte gefixt (ging nur mit Trucklevel 10)

## Version 1.3.1-45, _03.03.2014_

- Neuer Textbind: /car lock [1-9]
- /kafk entfernt (wird mit dem neuen AFK-System nicht mehr benötigt)
- Anpassung an die Änderungen im Wantedkatalog: /sstvo gibt immer 15 WPs, /lstvo wurde für leichte StVO-Vergehen neu eingeführt - weitere Änderungen siehe /wpbinds

## Version 1.3.0-44, _11.01.2014_

- /kfish an neue Texte angepasst
- /vs leicht angepasst und Orte geändert
- /youtube search: Anzeige gefixt
- Bei /inettest wird der TS-Server nicht mehr angepingt
- In den Einstellungen kann festgelegt werden, ob die /trucking-Missionen aufsteigend oder absteigend angezeigt werden sollen. Außerdem kann man die Ergebnisse nun auch nach der Entfernung zum Kaufort sortieren!
- Grove Street: /plants etwas abgeändert
- Es ist nun möglich, ein abgeändertes Design zu nutzen. Bisher gibt es nur das Design "Epic White", das wird sich aber hoffentlich bald ändern. Das bisherige Erscheinungsbild ist immer noch standardmäßig ausgewählt, in den Einstellungen könnt ihr jedoch ein anderes Design wählen. Außerdem könnt ihr euch ein eigenes HTML-Design erstellen und dieses nutzen. Wenn ihr findet, dass das gut aussieht, werde ich es vielleicht auch als offizielles Design anbieten. Alle Fragen zu den Designs bitte im Thread stellen!
- Neuer Textbind für die LCN: /ssp (i.A. shadowlightning)
- CMD-Spam wird besser verhindert
- Statt /sperrgebiet, /sperrgebiet2, /bflucht bzw. /beamtenverweigerung können Staatsfraktionen nun auch /sg, /sg2, /bhzf bzw. /bv nutzen, um entsprechende WPs zu vergeben. Die alten Befehle sind weiterhin verfügbar
- Neue Fraktion: Ballas Family
- Textbinds der LCN gefixt
- Neue "Schon gewusst?"-Box bei den Infos, in der Tipps und Fakten zum sBinder stehen

## Version 1.2.3-43, _15.11.2013_

- Die Grove Street hat jetzt auch einen Überfall-Bind sowie 3 neue "Sprüche"
- Alle Staatsfraktionen haben nun den Textbind /vs. Mit dabei ist eine automatische Ortserkennung, die normalerweise recht präzise funktionieren sollte. Falls etwas nicht passt, könnt ihr einen Ort vorschlagen, den Namen ändern lassen, einen Ort verschieben oder auch löschen lassen.
- Alle Drogenpreise der Gangs in den Fraktionsbinds abgeändert. [[Quelle](http://forum.nes-reallife.de/board38-fraktionen/board105-scarfo-family/board106-allgemein/162840-abkommen-der-gangs-drogen/)]
- Verbesserungen der Zuverlässigkeit der meisten Abrufe von Daten aus dem Internet

#### Nachträglich (Build 43.1)

- Großer Bug, unter Anderem im Updatesystem, behoben
- **Dieses Update muss manuell heruntergeladen werden, wenn vorher Version 1.2.3-43 genutzt wurde!**

## Version 1.2.2-42, _15.09.2013_

- Bei /setjob werden nun viele verschiedene Berufsnamen akzeptiert
- Mit /carvalue kannst du prüfen, wie viel dein Fahrzeug wert ist (Neupreis ohne Addons, Neupreis mit Addons, Wert bei /car sell)
- Bug bei der Bundeswehr gefixt ("Betrete Mainbase mit...")
- Die Fraktion Korsakow Familie wurde durch die Grove Street ersetzt
- Verbessertes Update-System: Deutlich schneller, die sUpdate.exe wird nicht mehr benötigt!

## Version 1.2.1-41, _06.09.2013_

- Änderungen der WP-Binds: /gruppierung -> /ggs, /serienmord -> /smord, /sstvo erkennt per /checkwanted, ob es der 1. oder 2. Fall ist
- Mit /youtube search zeigt der sBinder gleich 10 Suchergebnisse einer YouTube-Suche an, aus denen dann eins ausgewählt werden kann
- Neue Fraktionsbinds der Scarfo Family, Änderungen beim Taxiteam

## Version 1.2.0-40, _30.08.2013_

- Einige Fraktionsbinds wurden abgeändert und neue hinzugefügt
- Neue Fraktion: San Andreas Media AG
- Bei der Berechnung des Fahrzeugwerts (/car sell) werden nun 25% statt 50% genommen
- Der sBinder kann mit dem Startparameter "--start-minimized" minimiert (in der Trayleiste) gestartet werden
- /youtube geht wieder und läuft jetzt über die Google API, das heißt für euch: schnellere Ladezeiten!
- Bei /respekt werden weitere Informationen angezeigt, wenn man Premium hat
- Neues Feature für die LCN. Mehr Informationen bekommt ihr von ChackN0rris
- Beim Job Geldtransporter gibt es die Option, dass der /moneyload-Dialog automatisch geschlossen wird
- Der Adminrang/die Admingruppe wird bei [NeS]lern (nicht bei Volunteers!) bei /playerinfo angezeigt
- Neuer Textbind: /membersall
- /weather wurde zu /wetter umbenannt. Grund: Adminbefehl
- Neue Lizenz, diese müsst ihr akzeptieren, um den sBinder nutzen zu können
- Die /me-Texte werden nicht gesendet, wenn der sBinder deaktiviert ist
- Der sBinder sollte nicht mehr spammen (CMD-Spam-Meldungen), sowohl bei eigenen Binds als auch bei Textbinds wie /ksell. Falls es noch zu Problemen kommt, meldet mir diese bitte.
- Viele interne, kleinere Änderungen
- Neue Jobs, Jobbefehle usw. - Eventuell müsst ihr euren Job neu auswählen, schaut da bitte mal nach

## Version 1.1.10-39, _15.06.2013_

- /kdonut kauft nun 20 Donuts
- Auch das Icon des Updaters wird nun in seiner eigentlichen Qualität angezeigt
- WPs angepasst: /sperrgebiet -> 61 WPs, Neu: /sperrgebiet2: Betreten eines Sperrgebietes (Außengelände Flugzeugträger) -> 30 WPs
- Neue Fraktion: Scarfo Family
- Die Telefonbinds (/p, /h, /ab) werden nur noch gesendet, wenn der sBinder nicht mit Entf deaktiviert wurde
- Eine Box, die euch auf dem Desktop anzeigt, wie lange ihr schon auf dem Desk seid, kann in den Einstellungen aktiviert werden

#### Nachträglich (Build 39.1)

- Fichwartezeit für Fraktionen auf 2 Sekunden runtergesetzt
- Neue Fahrzeugpreise im Fahrzeugrechner

## Version 1.1.9-38, _05.06.2013_

- /kinfo und /kversion entfernt. Nutzt stattdessen z.B. /kstate
- Anwalt als Beruf hinzugefügt
- Alles ans neue \_[AFK]-System angepasst
- Bug beim Belegen der Fraktionsbinds gefixt
- Bei /cpu wird bei Laptops auch der Akkustand angezeigt
- Komplette Neugestaltung der Einstellungen (aufgrund von Platzmangel)
- Programme können nun beim Start mitgestartet werden (-> Einstellungen, Seite 3)
- Kontextmenü für das "Dein Name"-Feld hinzugefügt

## Version 1.1.8-37, _25.05.2013_

- Neue Textbinds: /kstate, /frakall
- Beim Ordnungsamt wird bei /carticket nicht mehr der Motor ausgeschaltet
- /kfish an neue Texte angepasst
- Alle Systeme (z.B. /playerinfo, /leaders, /membersonline) ans [AFK]-System angepasst
- Bei /youtube sollte es nicht mehr zu starken Laggs kommen
- Notizen werden wieder gespeichert
- Das Icon wird nun in seiner eigentlichen Qualität angezeigt
- Bei aufgetretenen Fehlern wird man in der Infobox darüber benachrichtigt
- Bei /playerinfo wird auch der Ehepartner angezeigt, wenn der Spieler verheiratet ist
- Neue Fraktion: Korsakow Familie
- Verbessertes Speichern. Alle Hotkeys, die geändert wurden, sollten gleich funktionieren, die entfernten sollten ohne Neustart nichts mehr machen.
- Option "Automatischer Versionscheck" in den Einstellungen entfernt. Sie ist natürlich standardmäßig aktiviert
- /slsd der LCN geht wieder. Außerdem hat die LCN einen neuen Fraktionsbind
- Atommüll-Text der Bundeswehr geändert

## Version 1.1.7-36, _17.05.2013_

- Bug beim Öffnen einer ini-Datei behoben
- Neu im Datei-Menü: "Speichern unter..."-Funktion
- Links zu Forum usw. gefixt
- Weitere Bugs aufgrund des Serverumzugs gefixt, unter Anderem auch die "SAMP starten"-Funktion
- /youtube geht nun wieder
- /calc wurde gefixt
- Die Funktionen /membersonline bzw. /checkfrak, /leaders, /weather, /playerinfo und /trucking können nur alle 10 Sekunden aufgerufen werden

## Version 1.1.6-35, _11.05.2013_

- Bug bei /kbl gefixt
- Neuer Textbind: /kfishes
- Neue Server-IP (diese muss nie wieder geändert werden)
- Einige kleiner Bugfixes
- Das Öffnen einer ini-Datei über Datei->Öffnen ist nun möglich
- Hoffentliches Fixen eines Bugs, bei dem der sBinder ohne Grund pausiert wurde
- In den Menüs werden Icons genutzt

## Version 1.1.5-34, _04.05.2013_

- Neue Textbinds: /druginfo, /kame multi, /kbl, /membersonline id (/checkfrak id), /leaders id, /calc
- Neue Fraktion: Yakuza
- Bug bei /setmoney gefixt
- Bug bei Texteingabe in Dialogen (Passwort, Report, ...) gefixt
- Verbesserte Ansicht des Changelogs und der Textbinds
- Neuer Standard-Downloadmodus. Dieser sollte Aufhänger oder Fehler bei irgendwelchen Downloads verhindern. Meldet euch bitte umgehend, falls er nicht korrekt arbeitet.
- Die Anzahl der eigenen Binds (Hotkeys) wurde von 30 auf 52 erhöht (auf 2 Seiten verteilt). Die Maustasten haben eine eigene Seite.
- Die Anzahl der eigenen Textbinds wurde von 17 auf 26 erhöht.
- Beim Klicken auf die Anzahl der markierten Aufträge im Trucking-Fenster werden die markierten Aufträge in die Zwischenablage kopiert.
- Neuer Befehl fürs FBI: /kaufstellung (andere Fraktionen auf Anfrage)
- Es wird nun hauptsächlich der AppData-Ordner statt dem Temp-Ordner benutzt
- Bei /trucking wird bei Aufträgen, die einen speziellen Anhänger benötigen (ab Truckerlevel 8), der benötigte Anhänger angezeigt

## Version 1.1.4-33, _28.04.2013_

- Der Text, der nach dem Login eingegeben wird (vorher immer /hitsound), kann nun selbst gewählt werden
- Verbessertes Annehmen eines Auftrags beim TaxiTeam
- Neuer Button in den Einstellungen: "sBinder-Ordner öffnen"
- Verschönertes Update-System
- Kleines Easteregg im sBinder versteckt. Wer es findet darf es behalten.
- Neue Fraktion: La Cosa Nostra
- Bei /setmoney sind nun auch Angaben wie 1,2k oder 1.000 \$ möglich

## Version 1.1.3-32, _20.04.2013_

- Aktualisierung der WP-Binds (siehe /wpbinds)
- Bugfix bei /ksell mit Premium
- Verbesserte Darstellung der Informationen
- Neues System für Umfragen (zu finden im Menü unter Sonstiges->Umfragen)
- Bei Eingaben (z.B. bei /playerinfo) sollte nun auch das Einfügen von Daten aus der Zwischenablage (Strg+V) funktionieren
- Neuer Textbind: /kautosetup
- "Rechts ranfahren"-Text der Bundeswehr erneuert. Außerdem wurde ein neuer Bind hinzugefügt.
- /membersonline, /leaders und /playerinfo wurden auch beschleunigt
- Neue Fraktion: Taxiteam

## Version 1.1.2-31, _13.04.2013_

- Die Missionen bei /trucking können in den Einstellungen nach eigenem Bedarf sortiert werden
- /trucking, /weather, /playerinfo, /membersonline bzw. /checkfrak und /leaders hat nun keine Fehler beim Download mehr! Dadurch sind /weather und /trucking außerdem um einiges schneller geworden (die anderen folgen...)
- Neue Textbinds: /ksell, /kfish - Ihr könnt diese natürlich auch mit Tasten nutzen, indem ihr sie in den Eigenen Binds als Befehl angebt.

## Version 1.1.1-30, _09.04.2013_

- Bei /playerinfo kann man auch eine ID oder eine Handynummer eingeben. Außerdem wurde ein Bug gefixt.
- Kleiner Bug bei /p gefixt
- Neue Textbinds: /kstop, /ktzelle
- Einige kleine Bugfixes und Verbesserungen
- Während der NSC nicht genutzt wird, wird der Connect-Button wieder SAMP starten
- Für einige Textbinds gibt es jetzt kürzere Formen, die alten Formen können allerdings immer noch verwendet werden (/bearbeite notiz -> /bnotiz; /kpayday -> /kpd; /lösche notiz -> /lnotiz; /membersonline -> /checkfrak; /paydaytime -> /pdt; /zeige notiz -> /znotiz)
- Bei /trucking und im Trucking-Fenster wird nun auch der Gewinn angezeigt

## Version 1.1.0-29, _31.03.2013_

- Neue Texbinds: /playerinfo, /setjob, /textbinds
- Die API kann in den Einstellungen aktiviert werden, muss aber nicht. Damit sollte ich sowohl denen gerecht werden, bei denen die API nicht funktioniert, als auch denen, die die API fordern.
- Kleiner Bug bei /membersonline und /leaders gefixt
- Texte für /p, /h und /ab (Anrufbeantworter) sind in den Einstellungen belegbar
- Kleiner Bug beim Auswählen von Pfaden gefixt
- Wenn der sBinder beim ersten Start auf dem Desktop liegt, wird man gefragt, ob man ihn verschieben und nur eine Verknüpfung auf dem Desktop erstellen will.
- /kdesk wird zu /kafk: Wenn man noch nicht AFK ist, geht man AFK und dann auf den Desk, ansonsten geht man aus dem AFK-Modus
- Neuer Textbind fürs PD, Bundeswehr und FBI: /takedrogenall
- Neuer Bind fürs FBI. Außerdem haben PD, FBI, Bundeswehr und der Rettungsdienst jetzt auch /mv als extra Bind.
- PD, FBI, Bundeswehr und das O-Amt haben nun auch /wpbinds als Textbind
- Es gibt die Möglichkeit, eigene Textbinds zu setzen! Sie funktionieren wie eigene Binds, deshalb sind sie auch unter den eigenen Binds zu finden. Allerdings kann es zu Problemen kommen, deshalb sind sie nur testweise im Keybinder.
- Man kann nun in den Einstellungen auch eigene Radio-Slots belegen, die man dann per /radio abrufen kann
- Die Jobs sind endlich im sBinder drin!
- Unter /kcmd stehen nur noch Textbinds, die den Keybinder selbst steuern, die restlichen Textbinds erhält man mit /textbinds. Außerdem erhält man Erklärungen zu den Textbinds mit /textbinds [1-4]

#### Nachträglich (Build 29.1)

- Neuer Bind für die Bundeswehr: /cc Sie sind festgenommen
- Ein Bug bei den eigenen Textbinds wurde gefixt

## Version 1.0.7-28, _26.03.2013_

- Übersichtlichere Gestaltung der Einstellungen
- Die Einstellung "/trucking: /cc statt /c benutzen" wurde entfernt. Sie ist nun standardmäßig aktiviert.
- Neue Radiosender: BigFM, iloveradio
- Neue Fraktion: Dillimore Devils

## Version 1.0.6-27, _21.03.2013_

- Beim Ablaufen des Timers wird ein Ton abspielt. Außerdem wird die Zeit angezeigt, bei der der Timer ablaufen sollte (±1 Sekunde)
- Debug-Informationen können im Menü unter Sonstiges->Debug-Informationen anzeigen abgerufen werden. Sie sollten bei Problemen angegeben werden
- Bei /cpu wird auch die RAM-Nutzung angezeigt
- Neuer Textbind: /leaders
- Mit Strg+S kann jetzt auch gespeichert werden
- Das Police Department hat nun auch "richtige" Fraktionsbinds
- Neue Option in den Einstellungen: Automatisch /hitsound
- Auch das Neigen des Mausrads nach links/rechts kann als Taste für eigene Binds verwendet werden. Allerdings funktioniert das nicht bei jeder Maus (bei manchen wird es auch als Maustaste 4/5 erkannt)
- Der Rettungsdienst hat nun auch /cancel revive als Bind
- Neue Fraktion: Bundeswehr
- Der Schriftzug (Bild im Hauptfenster) wird beim Start heruntergeladen

## Version 1.0.5-26, _12.03.2013_

- Neue Textbinds: /radio, /radio list, /chatlogbackup
- Bei /kcmd werden die Befehle nach dem Alphabet sortiert
- Die sBinder-Daten und -Dateien können nun über die Einstellungen gelöscht werden
- Bug bei /housewithdraw all und Beträgen über 1000\$ gefixt
- Neue Fraktion: FBI
- Update des Fahrzeugrechners
- Maustasten können als Tasten für eigene Binds genutzt werden

## Version 1.0.4-25, _04.03.2013_

- Neues Icon und neuer Schriftzug (danke dafür an [L]ucius)
- Neues Design der sUpdate.exe
- Kleiner Fehler beim Suchen nach Updates behoben
- Der Pfad des Chatlogs kann nun geändert werden, da es bei einem Nutzer Probleme gab. Außerdem kann die INI-Datei über die Einstellungen geöffnet werden.
- /übungen wurde fürs Ordnungsamt angepasst. Außerdem wird bei /radar die ID des Geblitzten angezeigt.
- /clearchat berücksichtigt jetzt auch /pagesize
- Neue Einstellung: Wartezeit auf den Chatlog
- Neuer Textbind: /membersonline
- Neuer Aufbau der Einstellungen

## Version 1.0.3-24, _23.02.2013_

- Schnelleres Senden
- Neue Fraktion: Rettungsdienst
- Neue Einstellungen: Ins Tray minimieren, Ausblendeeffekt deaktivierbar, Anzeigen der Bilder im Trucking-Fenster
- Eigener Speichern-Button im Menü
- Neues Fenster zum Testen des Keybinders (oder auch anderer Binder). Nützlich, um Probleme zu reproduzieren. Allerdings funktionieren manche Text- und Fraktionsbinds in dem Fenster nicht so wie im Spiel. Es ist aufrufbar im Menü unter Sonstiges->Keybinder testen
- Besseres Deaktivieren der Fraktionsbinds mit /togfrakbinds

## Version 1.0.2-23, _12.02.2013_

- /mv zu Ordnungsamt-Bind (/towopen) hinzugefügt. Außerdem gibt es wieder "Heli startet/landet".
- Neue Textbinds (/weather, /kme)
- Neue Einstellungen für /trucking hinzugefügt (unter Datei->Einstellungen)
- Hilfetexte zu den Einstellungen hinzugefügt (?-Buttons)
- /me-Texte für die Animationen (in den Einstellungen (de)aktivierbar)
- Beim ersten Keybinder-Start wird der Name automatisch ausgelesen
- Bug beim Speichern gefixt (Die Fraktionsbinds haben nicht mehr funktioniert)
- Police Department als Fraktion hinzugefügt (aktuell nur WP-Textbinds und /übungen, /showstaat)
- Bug mit Sonderzeichen bei /youtube behoben

## Version 1.0.1-22, _04.02.2013_

- Bug gefixt, bei dem Tasten "hängengeblieben" sind
- Senden ein wenig verschnellert
- Bug beim Annehmen von Aufträgen (Ordnungsamt) gefixt
- /music beendet nun alle anderen VLC-Instanzen
- Neue Textbinds (/youtube, /setmoney, /showpolice)
- Wenn ein Timer ausläuft und man nicht ingame ist, bekommt man trotzdem eine Benachrichtigung (MsgBox). Auch /countdown wird abgebrochen, wenn man auf den Desk geht.
- Trucking-Fenster erweitert: Bilder der Orte werden nun beim Anklicken angezeigt
- Deutlich schnellerer Start (Einige Dateien zusammengeführt)

## Version 1.0.0-21, _21.01.2013_

- Auslesen des Chats verbessert
- Falls der sBinder nicht mit Adminrechten gestartet wurde, wird er automatisch mit Adminrechten gestartet (ihr bekommt dann ein Fenster von der Benutzerkontensteuerung), da er ohne Adminrechte möglicherweise nicht richtig funktioniert.
- Einige Verbesserungen beim Update-System
- Neue Textbinds (/trucking, /music)
- (Vorübergehendes) komplettes Entfernen der API aufgrund der Kompatibilität zum NSC. Lookie und Feet wollen evtl. eine eigene API entwickeln, die nur noch wenige Funktionen beherrscht.
- Neues Trucking-Fenster
- Einige kleinere Verbesserungen und Anpassungen (z.B. /ksms, /kcall)
- Verbessertes Speichern
- Einige Textbinds und Funktionen wurden entfernt, da sie ohne API nicht mehr funktionieren (/kskinid, /kheal, /kcarheal, /kort, /kpos, /headup, Head-Up-Display, /overlay, /vehicstate)
- Um Fehler, z.B. beim Login, zu vermeiden, wird nun beim Drücken von Entf ein Ton (aktiviert) bzw. zwei Töne (deaktiviert) abgespielt.
- Man kann nun Textbinds auch bei [InputMode] benutzen, allerdings kann es zu kleinen Veränderungen bei der Reihenfolge kommen.
- Ein Countdown kann mit Entf abgebrochen werden
- Die Nova-Connect-Funktion startet nun den NSC
- Falls TS^3^ schon gestartet ist, wird es mit TS3-Connect nicht erneut gestartet
- Neue Version des Fahrzeugrechners

**Hinweis:** Ihr könnt nun in den eigenen Binds nur noch die Wörter [Name] und [ID X] benutzen, folgende funktionieren nicht mehr: [Level], [Money], [ID], [Skin], [Heal], [Armor]
**Hinweis:** Die Texte, die früher (mit der API) nur ihr sehen konntet, werden nun per /c an den Server gesendet, somit können sie von anderen Spielern nur gesehen werden, wenn sie sehr nahe bei euch sind. Außerdem werden damit keine Live-Gespräche oder Ähnliche gestört.

## Version Open Beta 0.9.1-20, _28.12.2012_

- Verbesserungen bei einigen Textbinds
- Wenn man im Ordnungsamt ist und vor dem Verwahrplatz steht, wird das Tor mit Doppelhupe geöffnet
- Hinweis bei /kexit und /krestart hinzugefügt
- /kfl, /kkmh entfernt
- /housewithdraw all an das Update angepasst
- Die URLs bei /inettest angepasst
- Die Fraktionsbinds vom Ordnungsamt etwas angepasst
- Neuer Textbind: /clearchat
- Speedbug- und Sprint-Funktion entfernt (nicht erlaubt)

## Version Open Beta 0.9-19, _15.12.2012_

- Kleiner Bugfix im Updatesystem
- Bei /countdown wird man zuerst gefragt, in welchen Chat man schreiben will. Man kann dort zum Beispiel /s, /d, /r, /f, /news, ... eingeben
- Der Textbind /countdowns wurde entfernt, nutzt dafür /countdown
- Die Daten werden nicht mehr im data-Ordner abgelegt, daher wird der data-Ordner nicht mehr benötigt
- Aktuelle Informationen werden unten im Hauptfenster angezeigt
- Sprinten verbessert
- Bei den eigenen Binds werden nun auch "[Money]", "[Skin]", "[Heal]" und "[Armor]" durch die jeweiligen Werte ersetzt
- Die Connect-Funktion funktioniert jetzt (hoffentlich) besser

## Version Open Beta 0.8.3.1-18, _10.12.2012_

- CopyRight-Hinweis im Über-Menü hinzugefügt
- Bei den eigenen Binds wird nun auch "[Level]" durch das Level ersetzt
- Bei /uhr wird auch der Wochentag angezeigt

## Version Open Beta 0.8.3-17

- Bug gefixt, bei dem das Head-Up-Display in einer Zeile angezeigt wurde
- Neue Textbinds (/vehicstate, /timer, /timermin, /countdown, /countdowns, /stoppuhr, /uhr)

## Version Beta 0.8.2-16

- Neue Textbinds (/kcmd, /cpu)
- Verbessertes Updatesystem
- Anzahl der eigenen Binds von 20 auf 30 erhöht
- Nun kann man bei /zeige notiz und /lösche notiz auch "all" eingeben

## Version Beta 0.8.1-15

- Neues Logo
- Neue Feedback-Funktion
- Man kann nun die Texte "[ID]" und "[Name]" in den eigenen Binds verwenden, diese werden beim Absenden automatisch mit der aktuellen ID oder dem Namen (angegeben unter "Dein Name:") ersetzt. Beispiel: "/oos /showperso [ID]".
  Außerdem kann man nun auch ID-Binds in die Eigenen Binds packen, dies funktioniert z.B. so: "/sex [ID 1][id 2]". Man kann das natürlich nicht nur für IDs verwenden, sondern auch für andere Zahlen, Namen oder sogar ganze Texte.
- Neuer Textbind (/showstaat)

## Version Beta 0.8-14

- Bugfixes gegen API-Fehler
- Neue Overlay-Funktionen zur Healanzeige (ohne Cleo/asi, auf Nova erlaubt)
- Neue Textbinds (/overlay, /paydaytime, /respekt, /kcall, /kgeld, /kexit, /housewithdraw all)
- Bei den Eigenen Binds kann man jetzt [InputMode] vor den Text stellen, um ihn normal (nicht per API) abzusenden. So kann man zum Beispiel eine SMS an eine Nummer senden oder Ähnliches. Außerdem kann man die Pfeiltasten nutzen. ~ wird immer in ein Enter umgewandelt. Beispiel: [InputMode]t/car lock~[Wait 300]{down}~
- Wenn die D3DX9_43.dll fehlt und somit die API nicht geladen werden kann, erscheint beim Programmstart eine Meldung und ein Angebot zum Download
- Fahrzeugrechner hinzugefügt
- Neue Funktionen für das Ordnungsamt (/tt, /ttlist, /übungen)
- Bei einem Update wird man gefragt, ob man die Virustotal-Links öffnen will
- Man kann Textbinds jetzt auch über Eigene Binds aufrufen lassen! (funktioniert leider (noch) nicht bei [InputMode])
- Das Head-Up-Display kann nun auch als Beifahrer aktiviert werden, indem man /headup eingibt. Es ist aber standardmäßig deaktiviert
- Neue API-Version 0.8.1
- Wenn man einen Text eingeben muss (z.B. bei /kpayday die Zahlen) werden diese sicher nicht mehr in den Chat gesendet

## Update Version Beta 0.7-13

- Einige kleinere Bugfixes
- Neue API-Version Beta 0.8
- Neue Funktion: Doppelhupe = /mv (in den Einstellungen aktivierbar)
- Neue Textbinds (/inettest, /kdonut, /kame, /togfrakbinds, /kcancel)
- Neue Speedbug-Funktion

## Update Version Beta 0.6.1-12

- Der TS^3^-Connect connectet jetzt automatisch auf den Nova-Channel
- Wenn man den sBinder deaktiviert wird das verzögerte Senden (mit [Wait XXX]) auch abgebrochen
- Integrierte Hilfe (?-Buttons)

## Update Version Beta 0.6-11

- Kleine Bugfixes und Verbesserungen
- Neue Textbinds (/zeige notiz [Nummer], /bearbeite notiz [Nummer], /lösche notiz [Nummer])
- Notizfunktion hinzugefügt (Notizen werden automatisch gespeichert)
- Ordnungsamt zu den Fraktionen hinzugefügt
- Schnellere Überprüfung, ob Internetverbindung vorhanden ist (Ping)

## Update Version Beta 0.5.1-10

- Die Connect-Funktion wechselt nun einfach zu GTA, wenn GTA:SA:MP bereits geöffnet war
- Wenn man bei den eigenen Binds "[Wait (Zeit)]" eingibt, wartet der Keybinder Zeit ms, bis er den nächsten Befehl abschickt. Beispiel: /me schläft.~[Wait 10000]/me ist wieder wach.
- Neue Textbinds hinzugefügt (/kpayday, /kdesk)
- /reconnect wurde gefixt (es erscheint keine Fehlermeldung der API mehr)

## Update Version Beta 0.5-9

- Der Textbind /headup wurde hinzugefügt
- Head-Up-Display eingefügt (in den Einstellungen deaktivierbar)
- Im Menü "Sonstiges" gibt es nun den Menüpunkt "Nach Updates suchen"

## Update Version Beta 0.4-8

- Neue IP für Nova Connect
- Das Fenster "Wichtige Binds" wurde hinzugefügt

## Update Version Beta 0.3.2-7

- Einige Bugfixes

## Update Version Beta 0.3.1-6

- Autohotkey Version wird im Fenster "Über" angezeigt
- Wenn man ein Update einmal verneint hat, wird die Meldung nur noch in der Statusleiste erscheinen, nach einem manuellem Update erscheint die Meldung dann wieder

## Update Version Beta 0.3-5

- Die Textbinds /krestart und /reconnect wurden gefixt und verbessert (/reconnect funktioniert fast immer, /krestart haut euch nicht mehr auf den Desk)
- Überprüfung auf Updates in der Statusleiste unten links im Fenster
- Vor Updates wird man nun gefragt, ob man die Arbeit speichern will

## Update Version Beta 0.2.1-4

- Neue Textbinds hinzugefügt (/kinfo, /kversion)

## Update Version Beta 0.2-3

- Eigene Binds funktionieren jetzt wirklich! [Im Gegensatz zu anderen Keybindern muss man z.B. /car lock~ statt t/car lock~ schreiben, also ohne t davor!]
- Neuer Textbind hinzugefügt (/reconnect)
- Man kann den Keybinder nun mit Entf deaktivieren bzw. aktivieren

## Update Version Beta 0.1.1-2

- Erkennt, ob Internetverbindung vorhanden ist
- Der automatische Versionscheck kann in den Einstellungen deaktiviert werden
- Nach einem Update wird gefragt, ob der Changelog angezeigt werden soll

## Update Version Beta 0.1-1

- Automatische Updatefunktion eingerichtet
- Changelog begonnen
