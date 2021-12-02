---
title: Passwort (un) sicherheit
---

## Postillon
![postillon](img/postillon.png)

## Warum brauchen wir Passwörter?
- Authentisierung → Bezeichnet das Nachweisen einer Identität.
- Authentifizierung → Prüfung dieses Identitätsnachweises auf seine Echtheit

### Arten Authentifizierung
Wie kann ich mich noch authentifizieren?

### Wer bin ich? (Biometrie)
- Gesichtserkennung
- Fingerabdruck
- Iris
- Venen
- Handschrift

### Was hab ich?
- Chip Karten
- Schlüssel

### Was weiß ich?
- Passwörter
- Pins

## Anforderungen an ein Passwort
- Länge des Passworts:
  - mind. 12 Zeichen lang
- Entropie erhöhen:
  - Groß-/Kleinbuchstaben
  - Ziffern
  - Sonderzeichen

### Wichtig
- Länge wichtiger als Entropie
- Für jeden Dienst ein neues Passwort generieren!

## Umfrage
- Online Umfrage
- Laufzeit eine Woche
- 100 Teilnehmer

### Wie alt sind die Probanden?
![](img/alter.jpg)

### Wie lang sind ihre Passwörter?
![](img/länge_passwort.jpg)

### Wie komplex sind ihre Passwörter?
![](img/komplex.jpg)

### Verwenden sie gleiche Passwörter öfter?
![](img/öfter_benutzen.jpg)

## Angriffe auf Passwörter
- Passwortlisten
- Bruteforce
- Phishing

### Passwortlisten
- Penetrationstest Betriebsysteme haben Listen
- Bekannteste ist rockyou.txt 
- Sammlungen im Internet:
  - https://github.com/danielmiessler/SecLists
  - Collection #1-5 Total mit 1TB
- Tools zum Generieren von Passwortlisten

### Cupp
Erzeugt Listen mit Informationen über Opfer
![cupp](img/cupp.png)

### Bruteforce
Bezeichnet das Ausprobieren von Passwörtern

- Hashcat oder John the Ripper (Offline gegen Dateien, Datenbanken)
- Hydra (Online gegen Dienste)

### Phishing
Ist das Abgreifen von Privaten Informationen 
(E-Mail, Kreditkarten Informationen, Passwörtern) 
durch gefälschte E-Mail und Webseiten.

### E-Mail
![](img/phishing.png)

### gophish
Werkzeuge um Phishing Kampagnen zu fahren
![gophish](img/gophish.png)

### Wissen sie, was Phishing ist?
![](img/phishing.jpg)

## Lösungen
![](img/pflaster.png)

## 2FA

### Was ist 2FA?
Bezeichnet den Identitätsnachweis eines Nutzers mittels einer Kombination zweier unterschiedlicher und insbesondere unabhängiger Komponenten.

### Beispiele
![](img/2FA.jpg)

## Passwortmanager
Ein Safe für alle Fälle

### Was ist das?
Computerprogramm, mit dem sie ihre Passwörter für lokale Anwendungen und Online-Dienste speichern, generieren und verwalten können.

### Test
- KeepassXC
- Bitwarden

### KeepassXC
- Speichert ein Passwortcontainer auf einer Festplatte
- Ein Hauptpasswort
- Generation der Passwörter
- Verlust oder Defekt des Sicherheitsschlüssels kein Zugriff mehr

### UI
![](img/keepassxc.jpg)

### Bitwarden
- Cloud-Passwortmanager
- Synchronisiert über Apps und Desktop-Programme

### UI
![](img/bitwarden.png)

## FIDO2
Das Passwort der Zukunft!?

### Was ist das?
Ist ein Digitaler Schlüssel auf einem Gerät, häufig ein USB-Stick.
Prinzip basiert auf Asymmetrischer Kryptografie.

### Schlüssel
![](img/fido2.jpg)

### Modi
- Ein-Faktor-Authentifizierung
  - lediglich FIDO2-Stick; kein Passwort nötig, aber vom Dienst abhängig
-Zwei-Faktor-Authentifizierung
  - zusätzlich zum FIDO2-Stick noch PIN, Passwort oder Fingerabdruck

### Vorteil
Identitätsnachweis ohne persönliche Daten zu hinterlassen

### Nachteil
- Noch nicht von allen Diensten unterstützt
- Geräteverlust/-beschädigung
- Geräte mind. 20-100€

## Passwörter verloren?
- haveibeenpwned.com
- sec.hpi.de/ilc/search

## Welche Tools werden benutzt?
![tools](img/tools.jpg)

## Was solltet ihr jetzt tun?
- Heute gucken, ob euer Passwort verloren gegangen ist.
- Nächste Woche richtet ihr einen Passwortmanager ein.
- Und als letztes verseht ihr wichtige Logins mit 2FA.

## Quellen
- golem.de/news/bitwarden-und-keepassxc-wohin-mit-all-den-passwoertern-2009-151121.html
- bitwarden.com
- keepass.info
- heise.de/ct/artikel/Passwortloses-Anmelden-dank-FIDO2-4494951.html
- solokeys.com/de

## Q & A
![](img/Frage-und-Loesung.png)
