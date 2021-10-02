# BigBlueButton

## Allgemeines

BigBlueButton™ (BBB) ist ein **Open-Source-Webkonferenzsystem**, mit dem virtuelle Konferenzräume erstellt werden können. Der Funktionsumfang ist ähnlich zu Zoom, Microsoft Teams, Cisco Webex, etc.

BBB bietet u.&#x00A0;a. folgende **Funktionalitäten** an: <br/>
Audio- / Videochat, öffentliche und private Chats, Freigabe von Präsentationen und anderen Dokumenten, Bildschirmfreigaben, Whiteboard-Funktion (Multiuser), Einfache Umfragen, Breakout-Räume, ...

**Voraussetzungen für die Teilnahme an einer BBB-Konferenz?**

Für die Teilnahme an einer BBB-Konferenz wird lediglich ein Browser mit Unterstützung für WebRTC benötigt, was jeder moderne Browser unterstützt. Du musst somit keine weitere Software installieren. <br/>
Wir empfehlen für eine gute Audio- und Video-Qualität einen der folgenden Browser zu nutzen:

- Chromium-basierter Browser (z.&#x00A0;B. Google Chrome oder die datenschutzfreundliche Alternative [Ungoogled Chromium](https://ungoogled-software.github.io/ungoogled-chromium-binaries/){:target="_blank"}, Microsoft Edge, Vivaldi, ...)

- [Mozilla Firefox](https://www.mozilla.org/de/firefox/new/){:target="_blank"} ist eingeschränkt zu empfehlen, da es insbesondere für Referent:innen ungeeignet ist (bspw. ist die Bildschirmfreigabe weniger funktional und bietet nicht die Option an, das Systemaudio ebenfalls zu teilen)

**Warum setzen wir BigBlueButton ein?**

Auf der Seite [Zukunftsfähige Tools](zukunftsfaehig.md) haben wir erklärt, was "zukunftsfähige" Tools ausmacht und warum wir auf BigBlueButton als System für unsere Online-Veranstaltungen setzen.

## Verbindungsaufbau zur Videokonferenz

1. Rufe den **Link zur Videokonferenz** in einem der empfohlenen Browser auf. Den Link zur Videokonferenz bekommst du i.d.R. über die Seite der jeweiligen Veranstaltung auf der [Website der Nachhaltigkeitswochen](https://hochschule-n-bw.de/events/){:target="_blank"}.

2. Angabe deines **Namens** (der Name wird nur zur Anzeige in der Konferenz verwendet und nicht gespeichert).

3. **Betreten des Konferenzraums**
    Du wirst nun automatisch in den Konferenzraum weitergeleitet. Falls die Konferenz noch nicht gestartet wurde, wird ein entsprechender Hinweis angezeigt. Sobald die Konferenz dann gestartet wurde, wirst du automatisch in den Konferenzraum weitergeleitet.

4. **Mikrofon freigeben:**

    1. Wähle bitte aus, dass du mit **Mikrofon** an der Konferenz teilnehmen möchtest. Nur so hast du die Möglichkeit, dein Mikrofon überhaupt während der Konferenz zu verwenden. Bei "Nur zuhören" ist es nicht mehr möglich, während der Konferenz dein Mikro anzuschalten.

    2. Erteile deinem Webbrowser die **Berechtigungen**. Es ist sinnvoll den Haken für "Entscheidung merken" zu setzen, wenn du an mehreren Veranstaltungen teilnimmst. Eine nachträgliche Änderung der Berechtigungen ist durch einen Klick auf das Schlosssymbol möglich.
        <div style="display: flex;">
          <figure>
            <img src="../../img/bbb-mikrofon-firefox.png" alt="Firefox" width="300"/>
            <figcaption>Firefox<figcaption>
          </figure>
          <figure>
            <img src="../../img/bbb-mikrofon-chrome.png" alt="Chrome" width="300"/>
            <figcaption>Chrome<figcaption>
          </figure>
        </div>

    3. **Echotest:** Nach der Freigabe deines Mikrofons wird ein Echotest angeboten, der zur Funktionsprüfung der Audio-Verbindung dient. Stelle hierbei sicher, dass du dich selbst (mit leichtem Zeitversatz) hören kannst, aber keine [Rückkopplung](https://de.wikipedia.org/wiki/R%C3%BCckkopplung#Tontechnik){:target="_blank"} entsteht.

5. **Webcam freigeben**
    Um deine Webcam freizugeben, klicke in der unteren Leiste auf das Symbol mit durchgestrichener Kamera. Ggf. wirst du vor der Aktivierung aufgefordert, der Verwendung der Webcam durch den Browser zuzustimmen (äquivalent zur Zustimmung des Mikrofons).


## Benutzungsoberfläche

!!! abstract ""
    Auf dieser Seite werden die Funktionalitäten von BigBlueButton anhand der Oberfläche aus Sicht einer Person mit Präsentationsrechten erklärt.

**BBB-Oberfläche:**
<figure>
  <img src="../../img/bbb-oberflaeche.png" alt="BBB-Oberfläche" />
</figure>
<!--
**A:** [Interaktion mit anderen Teilnehmern](#a-interaktion-mit-anderen-teilnehmern)
**B:** [Aktionen](#b-aktionen)
**C:** [Mikrofon, Audio, Webcam und Bildschirmfreigabe steuern](#c-mikrofon-audio-webcam-und-bildschirmfreigabe-steuern)
**D:** [Präsentation/Whiteboard](#d-prasentationwhiteboard)
**E:** [Optionen](#e-optionen)
**F:** [Aufzeichnung der Veranstaltung](#f-aufzeichnung-der-veranstaltung)
**G:** [Layout anpassen](#g-layout-anpassen)
-->

### A: Interaktion mit anderen Teilnehmern

- **Öffentlicher Chat:** Nachrichten, die du hier versendest, können von allen Konferenzteilnehmer\*innen gelesen werden.

- **Geteilte Notizen:** An dieser Stelle können Texte gemeinsam mit anderen Teilnehmer\*innen verfasst werden. Die geteilten Notizen werden beim Beenden der Konferenz <ins>nicht</ins> automatisch gespeichert und müssen deshalb ggf. vorher manuell exportiert werden:
    <img align="left" src="../../img/bbb-notizen.png" alt="BBB Notizen" width="400" />
    <div style="clear:both"></div>

- **Teilnehmer\*in:**

    - Per Linksklick auf den Namen einer anderen Person kannst du einen "**Privaten Chat starten**".

    - Per Linksklick auf den eigenen Namen kannst du deinen **Status verändern** und dadurch z.&#x00A0;B. symbolisch die "**Hand heben**". Dies ist jedoch auch unten rechts mit dem Handsymbol möglich.

### B: Aktionen

*Die Aktionsmöglichkeiten stehen nur Personen mit Präsentationsrechten zur Verfügung*

- [Umfrage starten](https://support.blindsidenetworks.com/hc/en-us/articles/360024977292-Use-polling-){:target="_blank"}

- [Eine Präsentation hochladen](https://support.blindsidenetworks.com/hc/en-us/articles/360024688392-Upload-a-presentation-enable-for-download){:target="_blank"}

- [Externes Video teilen](https://support.blindsidenetworks.com/hc/en-us/articles/360025238131-Share-an-External-Video-Link){:target="_blank"}

### C: Mikrofon, Audio, Webcam und Bildschirmfreigabe steuern

- **Mikrofon freischalten/stummschalten:**
    Bitte achte darauf, dass dein **Mikrofon nur aktiviert** ist, wenn du wirklich etwas sagen möchtest.

- **Audio starten/beenden/ändern:**
    Hierdurch kann die Audio-Verbindung zur Konferenz ganzheitlich gestartet oder beendet werden oder ein anderes Mikrofon bzw. Lautsprecher ausgewählt werden. Im Normalfall sollte es während einer Konferenz keinen Grund geben die Audio-Verbindung auf diese Weise zu deaktivieren.

- **Webcam freigeben/Webcamfreigabe beenden:**
    Über diesen Button kannst du deine Webcam aktivieren und deaktivieren. Bei der Aktivierung kannst du ggf. noch Einstellungen zur Übertragungsqualität vornehmen, wobei du hier im Normalfall die voreingestellte Qualitätsstufe beibehalten kannst.

- **Bildschirm freigeben/Bildschirmfreigabe beenden:**
    *Diese Möglichkeit steht nur Personen mit Präsentationsrechten zur Verfügung.*
    [→Anleitung](https://support.blindsidenetworks.com/hc/en-us/articles/360025276251-Share-my-screen){:target="_blank"}

### D: Präsentation/Whiteboard

*Die Möglichkeit zum Präsentieren und der Verwendung des Whiteboards steht nur Personen mit Präsentationsrechten zur Verfügung. Wenn der\*die Präsentator\*in das Whiteboard freigegeben hat, können alle darauf arbeiten.*

- Anleitung: [Use the presentation controls](https://support.blindsidenetworks.com/hc/en-us/articles/360024689292-Use-the-presentation-controls){:target="_blank"}

### E: Optionen

- **Vollbild:** Ausblenden der Browser-Schaltflächen und Wechsel der eigenen BBB-Umgebung in den Vollbildmodus.

- **Einstellungen:** Hier können weitere Einstellungen für eigene BBB-Umgebung vorgenommen werden. Besonders hervorzuheben sind hier die Einstellungen zur Datenvolumeneinsparung im Falle von Problemen mit der Audio- oder Videoverbindung. Vor allem als Präsentator\*in könnte es relevant sein die Einstellung zu aktivieren, dass du bei neuen Nachrichten im Chat oder beim Beitritt weiterer Teilnehmer\*innen ein Audiosignal erhälst.


### F: Videos verschieben

- Durch Drag & Drop lassen sich die Videos über, unter oder neben die Präsentation verschieben.

### G: Layout anpassen

- Bewege den Mauszeiger zwischen Kamera-Bild(er) und Präsentation und verändere durch vertikales Bewegen des Mauszeigers bei gleichzeitig gedrückter linker Maustaste das Layout. 
    ![](https://support.blindsidenetworks.com/hc/article_attachments/360044515132/adjustwebcams.gif)

## Barrierefreiheit


BBB erreicht Level AA der WCAG 2.0 mit folgenden Einschränkungen:

- Die gezeigten Präsentationen und Dokumente können nicht barrierefrei über den Präsentationsmodus gezeigt werden. Sie müssen nach den Regeln für Barrierefreiheit gestaltet sein und den Studierenden anderweitig zugänglich gemacht werden.
- Das Fenster„gemeinsame Notizen“ ist nicht barrierefrei.
- Die Untertitelfunktion ist nur eingeschränkt barrierefrei.
- Die Hilfe ist nicht barrierefrei.
- Weitere Informationen finden Sie [hier](https://bigbluebutton.org/accessibility/){:target="_blank"}

### Tastenkombinationen

| Tastenkombination  |	Funktion                                                                |
|:-----------------  |:------------------------------------------------------------------------ |
| Alt + Shift + O    |	Einstellungen öffnen                                                    |
| Alt + Shift + U    |	Teilnehmerliste öffnen/schließen                                        |
| Alt + Shift + M    |	Stummschalten/Freischalten                                              |
| Alt + Shift + J    |	Audio starten                                                           |
| Alt + Shift + L    |	Audio beenden                                                           |
| Alt + Shift + P    |	Öffentlichen Chat öffnen/schließen (Teilnehmerliste muss geöffnet sein) |
| Alt + Shift + H    |	Privaten Chat verstecken                                                |
| Alt + Shift + G    |	Privaten Chat schließen                                                 |
| Alt + Shift + A    |	Aktionsmenü öffnen (+ unten links)                                      |
| Alt + Shift + S    |	Statusmenü öffnen                                                       |
| Leertaste          |	Aktiviere Verschiebewerkzeug (Präsentator)                              |
| Pfeil rechts       |	Nächste Folie (Präsentator)                                             |
| Pfeil links        |	Vorherige Folie (Präsentator)                                           |
