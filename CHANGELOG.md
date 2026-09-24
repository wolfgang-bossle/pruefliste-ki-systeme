# Änderungsprotokoll

Jede Fassung der Prüfliste und was sich geändert hat. Die PDF jeder Fassung hängen am
zugehörigen Release.

## v2.1 · Fassung 2.1

Die erste Fassung mit Rückmeldungen aus der Praxis. Eingearbeitet sind eine Durchsicht aller
Fragen an Systemen im Einsatz und der Hinweis auf eine Lücke zwischen zwei Fragen. Jede
Änderung unten folgt einem dieser Hinweise und ist wie in Fassung 2 mit dem wörtlichen Zitat
belegt, das sie trägt. Die Nummern sind die von Fassung 2.

**Geändert**

- **Frage 4, Modellentscheidung: Begründung und eingebundener Dienst.** Hinweis aus dem
  Rücklauf: Bei einem eingebundenen Dienst wählt dessen Anbieter das Modell und weist es nicht
  aus. Das Unternehmen kann dann nicht freigeben, was es nicht kennt. Das Beispiel für den
  ungenügenden Nachweis zeigt jetzt diesen Fall. Dazu fragt die Frage, was der Nachweis
  schon verlangte: „Wo ist festgehalten, wer welches Modell für diesen Fall freigegeben hat,
  mit welcher Begründung und an welchem Datum?“ Beleg erweitert: IDW AdvH 6.003 Tz. 93 Nr. 3
  (Intransparenz des fremdbezogenen Modells).
- **Frage 23, Wissensbasis: Datenstand je Antwort.** Hinweis aus dem Rücklauf: Keine Frage
  verlangte den Datenstand hinter einer einzelnen Antwort. Versioniert waren Konfiguration
  und Testlauf, der Stand der Daten nicht. Die Frage lautet jetzt: „Wie ist die Wissensbasis
  aufbereitet, und wo ist je Antwort festgehalten, auf welchem Datenstand sie beruht?“ Im
  Beispiel bleiben frühere Indexläufe mit ihren Fassungen gespeichert und abrufbar, statt
  überschrieben zu werden. Neue Belege: IDW PS 861 Tz. 31 (Änderungen an Daten und
  Datenquellen nachvollziehbar) und GoBD Rz. 89 (Tabellendaten und deren Historisierung
  gespeichert), letztere mit dem Hinweis, dass sie gilt, soweit Antworten in die Buchführung
  eingehen. Eine eigene Frage zur Aufbewahrung dieses Stands gibt es nicht: Wie lange
  aufbewahrt wird, fragt schon Frage 26.
- **Frage 26, Protokolle: Protokoll beim Anbieter.** Hinweis aus dem Rücklauf: Bei manchen
  Diensten entsteht das Protokoll beim Anbieter, und die Prüfliste sagte nicht, ob es als
  Nachweis zählt. Jetzt zählt es nur, soweit das Unternehmen es jederzeit abrufen kann und der
  Abruf im Vertrag mit dem Anbieter geregelt ist. Neue Belege: DSGVO Art. 28 Abs. 3 lit. h
  (Adressat ist der Auftragsverarbeiter) und KI-VO Art. 26 Abs. 6.
- **Frage 26, Protokolle: was nicht hineingehört.** Hinweis aus dem Rücklauf: Die Frage
  prüfte, ob protokolliert wird, nicht was. Bei der Durchsicht fanden sich in einem Protokoll
  Zugangsdaten, die dort nichts zu suchen hatten. Jetzt legt das Beispiel fest, dass Angaben
  zu Personen, die der Zweck nicht braucht, vor dem Speichern geschwärzt werden. Neuer Beleg:
  DSGVO Art. 25 Abs. 2.
- **Frage 21, gegengelesener Code: Autor ist nicht Urheber.** Hinweis aus dem Rücklauf:
  Schreibt das bauende System über eine Schnittstelle unter dem Namen eines Menschen, steht
  dieser Mensch als Autor da. Jetzt sagt das Beispiel, dass der Autor im Pull Request nur
  zeigt, wer die Änderung eingereicht hat; welche Zeilen Claude Code erzeugt hat, weist eine
  eigene Kennzeichnung am Pull Request aus. Neuer Beleg: Anthropic, Claude Code Analytics,
  Abschnitt „PR attribution“. Die acht Quellen der KI-Governance tragen diesen Punkt nicht.
- **Frage 31, Kosten: Mengengrenze ist keine Kostengrenze.** Hinweis aus dem Rücklauf: Ein
  Limit je Woche blockierte tatsächlich, begrenzte aber die Menge, nicht die Kosten. Jetzt
  steht im Beispiel für den ungenügenden Nachweis, dass eine Grenze für Anfragen oder Tokens
  je Minute die Menge bremst, eine Monatssumme aber nicht deckelt. Beleg erweitert:
  Anthropic, Workspaces.
- **Ausgangspunkt: welche es gibt und was daraus folgt.** Hinweis aus dem Rücklauf: Die
  Prüfliste sagte nicht, welche Ausgangspunkte es neben ihrem eigenen gibt. Unter
  „Anwendbarkeit“ verweist jetzt ein Satz auf den Anhang. Dessen neuer Teil D führt
  die Ausgangspunkte auf, vom fertigen Produkt bis zur Person, die für sich selbst baut, und
  zeigt, was daraus für die Beantwortung folgt: Fragen, die eine Abnahme verlangen, setzen
  getrennte Rollen voraus. Die weiteren Hinweise stehen jetzt in Teil E.
- **Frage 26, Zitate gekürzt** auf den tragenden Satz, damit die Frage auf einer Seite bleibt.

**Geprüft und nicht übernommen**

- **Eine Fassung ohne Rollentrennung.** Neun Fragen der Fassung 1 fragen nach „wer“ oder „für
  wen“ und sind nicht zu beantworten, wenn eine Person baut, betreibt und abnimmt. Die Prüfliste bleibt
  beim Ausgangspunkt der ersten Seite: Ein Dienstleister baut, das Unternehmen nimmt ab und
  betreibt.
- **Modell-ID ohne Datum als Alias.** Die Annahme trifft ab der Generation 4.6 nicht zu.
  Anthropic, Model IDs and versioning: „For the 4.6 generation and later, the dateless ID is
  the canonical model ID for that release. It maps to a single, fixed model snapshot.“ Für
  frühere Modelle gibt es solche Aliase weiterhin.
- **Nachrechnen einer Antwort als Prüfpunkt.** Vorgeschlagen war, eine Ausgabe aus
  Datenstand, Modellversion und Prompt nachzurechnen. Anthropic sagt beides nicht zu. Messages
  API zu temperature: „Note that even with temperature of 0.0, the results will not be fully
  deterministic.“ Model deprecations: „Requests to retired models will fail.“ Die Prüfliste
  fragt deshalb, ob festgehalten ist, was geantwortet wurde und auf welchem Stand.

## v2 · Fassung 2

Von Grund auf neu gebaut. Rückmeldungen aus der Praxis sind in dieser Fassung noch nicht
eingearbeitet; das folgt mit der nächsten.

- **Neuer Name:** „Prüfliste für KI-Systeme“ (Fassung 1: „Prüffragen für KI-Systeme“).
- **Nur deutsch.** Fachbegriffe stehen im Original in Klammern dahinter.
- **Zwei Dateien:** die Prüfliste und der Anhang mit der Herleitung.
- **Drei Phasen:** Auswahl, Bau, Betrieb. „Nachweis“ und der Block „Zusätzlich“ sind
  aufgelöst; jede Frage steht in ihrer Phase, und eine Frage, die nur gilt, wo es einen
  bestimmten Bauteil gibt, sagt das selbst.
- **Eine Seite je Frage:** die Frage, direkt darunter die Seite von Anthropic zum Thema,
  der Fall, der nicht genügt, mit seinen Mängeln, und ein erfundenes Beispiel, wie der
  Nachweis aussehen könnte.
- **Gemessen an den Quellen der KI-Governance:** jede Forderung neben dem wörtlichen Zitat,
  das sie trägt, mit Fundstelle, aus KI-Verordnung und Leitlinien der Kommission zu
  Art. 50, DSGVO, GeschGehG, GoBD, IDW PS 861, IDW AdvH 6.003 und CLOUD Act. Richtet sich
  eine Norm nicht an das Unternehmen, steht das dabei.
- **Ein Rahmenfall für alle Beispiele:** Die Muster GmbH lässt von einem Dienstleister
  KI-Unterstützung für ihr Rechnungswesen bauen, nimmt sie ab und betreibt sie.
- **Anfangsseiten:** Ausgangspunkt, was in der Prüfliste steckt, Anwendbarkeit, Einordnung,
  der Abschnitt „Keine Haftung“, die Übersicht aller Fragen, die Lizenz.
- **Je Frage die Anwendbarkeit:** n. a., liegt vor, liegt nicht vor.
- **Fassung und Stand** in der Fußzeile jeder Seite.

## v1 · Fassung 1

Erste Veröffentlichung. 24 Seiten, deutsch und englisch in einem Dokument, die Fragen
gegliedert nach Auswahl, Bau, Betrieb und Nachweis, jede mit einer Spalte, die benennt, was
als Antwort nicht zählt. Abgeleitet aus den vier Claude-Zertifizierungen.
