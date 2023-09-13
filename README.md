# Projekt-Dokumentation

☝️ Alle Text-Stellen, welche mit einem ✍️ beginnen, können Sie löschen, sobald Sie die entsprechende Stellen ausgefüllt haben.

John Broder, Gabriel Bischof, Ensar Yildirim

Gruppenname: 34

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
|       | 0.0.1   | ✍️ Jedes Mal, wenn Sie an dem Projekt arbeiten, fügen Sie hier eine neue Zeile ein und beschreiben in *einem* Satz, was Sie erreicht haben. |
|       | ...     |                                                              |
|       | 1.0.0   |                                                              |

## 1 Informieren

### 1.1 Ihr Projekt

Unser Projekt ist eine C#-Anwendung, welches Börsenkurse anzeigt und zu einer Portfoliomanagement-Software erweitert werden kann.

### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 1    |  Funktional     | Muss | Als ein User möchte ich den Wert meiner Aktie wissen, damit ich weiss ob ich ein möglichen Gewinne erzielt habe.|
| 2    |  Funktional     | Nuss | Als ein User möchte ich den Verlauf des Wertes grafisch angezeigt bekommen, damit ich sie mit anderen Aktien vergleichen kann. |   
| 3    |  Funktional     | Muss | Als ein User möchte ich immer den neusten Stand der Aktie haben, damit ich immer auf dem neusten Stand der Dinge bin.|
| 4    |  Qualität       | Kann | Als Benutzer möchte ich ein Portfolio meiner Aktien erstellen und verwalten, damit ich alle meine Investitionen an einem Ort sehen kann.  | 
| 5    |  Rand           | Kann | Als Benutzer möchte ich Benachrichtigungen erhalten, wenn eine meiner Aktien einen bestimmten Wert erreicht, damit ich informierte Kauf- oder Verkaufsentscheidungen treffen kann.|
| 6    |  Rand           | Kann | Als Benutzer möchte ich aktuelle Nachrichten über meine Aktien sehen, damit ich auf dem Laufenden bleibe und informierte Entscheidungen treffen kann.|



### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  | Programm ist geöffnet    |  ---------------               | Wert der Aktie wird angezeigt               |
| 2.1  | Aktie wurde angewählt    | Grafisch anzeigen              | Der Wert wird Grafisch angezeigt            |
| 3.1  |Progrmm wird neugestartet |------------------              | Aktien kurse werden neugeladen              |
| 4.1  |Progrmm ist geöffnet      | Ordner erstellen wird geklickt | Ordner wird erstellt                        |
| 4.2  |Ordner ist geöffnet       | Aktien werden ausgewählt       | Ordner mit den gewählten Aktien ist erstellt|
| 5.1  |Progrmm ist geschlossen   | -----------------------------  | Nachricht wird gesendet                     |
| 6.1  |Programm ist geöffnet     | Nachrichten sehen anklicken    | Aktuelle Nachrichten werden ausgegeben      |

✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, die der Testfall abdeckt, und `m` von `1` an nach oben gezählt. Beispiel: Der dritte Testfall, der die zweite User Story abdeckt, hat also die Nummer `2.3`.


## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A      | 20.09 | Alle                              | API finden                              | 30 min  |
| 1.B/ 3.A | 18.10 | Alle                              | API implementieren                      | 150 min |
| 2.A      | 25.10 | John Broder, Ensar Yilidirm       | Grafik erstellen und Anzeigen lassen    | 120 min |
| 4.A      | 25.10 | Gabriel Bischof                   | Portfolio der Aktien erstellen          | 90 min  |
| 5.A      | 01.11 | John Broder, Gabriel Bischof      | Benachrichtigungen zur Aktie erstellen. | 120 min |
| 6.A      | 01.11 | Ensar Yildirm                     | Nachrichten zur Aktie anzeigen lassen.  | 60 min  |
Total: 570 min

✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, auf die sich das Arbeitspaket bezieht, und `m` von `A` an nach oben buchstabiert. Beispiel: Das dritte Arbeitspaket, das die zweite User Story betrifft, hat also die Nummer `2.C`.

✍️ Ein Arbeitspaket sollte etwa 45' für eine Person in Anspruch nehmen. Die totale Anzahl Arbeitspakete sollte etwa Folgendem entsprechen: `Anzahl R-Sitzungen` ╳ `Anzahl Gruppenmitglieder` ╳ `4`. Wenn Sie also zu dritt an einem Projekt arbeiten, für welches zwei R-Sitzungen geplant sind, sollten Sie auf `2` ╳ `3` ╳`4` = `24` Arbeitspakete kommen. Sollten Sie merken, dass Sie hier nicht genügend Arbeitspakte haben, denken Sie sich weitere "Kann"-User Stories für Kapitel 1.2 aus.

## 3 Entscheiden

✍️ Dokumentieren Sie hier Ihre Entscheidungen und Annahmen, die Sie im Bezug auf Ihre User Stories und die Implementierung getroffen haben.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  |       |           |               |                   |
| ...  |       |           |               |                   |

✍️ Tragen Sie jedes Mal, wenn Sie ein Arbeitspaket abschließen, hier ein, wie lang Sie effektiv dafür hatten.

## 5 Kontrollieren

### 5.1 Testprotokoll

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |       |          |        |
| ...  |       |          |        |

✍️ Vergessen Sie nicht, ein Fazit hinzuzufügen, welches das Test-Ergebnis einordnet.

### 5.2 Exploratives Testen

| BR-№ | Ausgangslage | Eingabe | Erwartete Ausgabe | Tatsächliche Ausgabe |
| ---- | ------------ | ------- | ----------------- | -------------------- |
| I    |              |         |                   |                      |
| ...  |              |         |                   |                      |

✍️ Verwenden Sie römische Ziffern für Ihre Bug Reports, also I, II, III, IV etc.

## 6 Auswerten

✍️ Fügen Sie hier eine Verknüpfung zu Ihrem Lern-Bericht ein.
