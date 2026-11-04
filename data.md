# Daten-Zeilen

## app_data_start — Stat-Zeile im Start-Untertitel

Wo: Startseiten-Untertitel, im selben Wurf wie die Start-Zeilen: an Tagen ohne passende Start-Situation immer, sonst bei der Hälfte. Eine Person, die heute vorn liegt bei KOs, Selbst-KOs, Siegen oder Stunden ohne Sieg ({h}).

Platzhalter: {name} {games} {kos} {selfko} {wins} {h}

- Tischschreck: {name}, {kos} KOs bisher.
- Kaffeekocher: {name}, {selfko}× selbst rausgeflogen.
- Dauergast: {name}, {h} Stunden am Tisch, kein Sieg.
- {name}: {kos} KOs. Die Hütte ist stolz.
- {name}: {games} Spiele, {games} neue Ausreden.
- {name}: {selfko}× den Tisch verlassen. Freiwillig?
- {name}: {h} Stunden am Tisch, noch immer überzeugt.
- {name}: {kos} KOs. Das Meta beobachtet.
- {name}: {games} Spiele lang den Shuffle beschuldigt.
- {name}: {wins} Siege. Die anderen nennen es Glück.
- {name}: {selfko}× selbst für Interaktion gesorgt.
- {name}: {kos} KOs. Die Personalplanung läuft.
- {name}: {games} Spiele. Die Akte wächst.
- {name}: {wins} Siege. Die Sitzungsleitung liegt nahe.
- {name}: {h} Stunden am Tisch. Noch nicht abgemeldet.
- {name}: {kos} KOs. Die Stuhlbelegung sinkt.
- {name}: {games} Spiele, {games} Gelegenheiten zur Nachbesprechung.
- {name}: {wins} Siege. Der Bericht wird vorbereitet.
- {name}: {kos}× die Tagesordnung verändert.

## app_data_nemesis — Nemesis und KO (Profil, Rivalen)

Wo: Eigenes Profil, Karte „Rivalen“. {nemesis} wirft dich am häufigsten raus ({n} Mal), du {victim} ({v} Mal); je ab 3.

Platzhalter: {nemesis} {n} {victim} {v}

- {nemesis} hat dich schon {n}× rausgeworfen. Therapie?
- Dein Lieblingsopfer: {victim}, {v}×. {victim} weiß Bescheid.
- {victim} fliegt meistens vor dir raus.
- {nemesis} kennt deine Schwachstelle: den eigenen Zug.
- {victim} war {v}× zur falschen Zeit am falschen Tisch.
- {nemesis} hat dich {n}× erwischt. Zufall?
- {victim} ist statistisch gesehen kein Langzeitprojekt.
- {nemesis} und du: eine toxische Meta-Beziehung.
- {victim} kennt deine Wincon inzwischen auswendig.
- {nemesis} hat dein Deck besser verstanden als du.
- {victim} sollte deine Starthand künftig prüfen.
- {nemesis} hat dich {n}× aus dem Programm genommen.
- {victim} war {v}× nicht mehr stimmberechtigt.
- {nemesis} kennt deine Tagesordnung inzwischen.
- {victim} hat den kürzeren Sitzungsverlauf.
- {nemesis} hat deinen Plan schon auf dem Tisch.
- {victim} und du: eine kurze Geschäftsbeziehung.
- {nemesis} hat deinen Stuhl reserviert. Für später.
- {victim} wurde {v}× aus der Sitzung entlassen.

## app_data_deck — Deck-Unterzeile

Wo: Unter dem Decknamen in der Deckliste und auf der Deckseite, ab 5 Spielen mit dem Deck. {dry} = Spiele seit dem letzten Sieg.

Platzhalter: {games} {wins} {dry}

- {games} Spiele, {wins} Siege. Das war der Shuffle.
- {wins} Siege. Respekt fürs Durchhalten.
- Seit {dry} Spielen ohne Sieg. Noch ein Mulligan?
- {dry} Spiele ohne Sieg. Das Deck bittet um Geduld.
- Letzter Sieg: vor {dry} Spielen. Die Liste wird geprüft.
- {games} Spiele, {wins} Siege. Der Rest war Lernmaterial.
- {wins} Siege. Das Deck darf bleiben.
- {games} Spiele. Der Gameplan wird noch gesucht.
- {wins} Siege. Die Liste hat sich bewährt. Angeblich.
- {games} Partien, {wins} Siege. Die Statistik ist höflich.
- {wins} Siege. Der Rest bleibt unter Verschluss.
- {games} Spiele, {wins} Siege. Weiter testen.
- {wins} Siege. Das Deck fordert eine Gehaltserhöhung.
- {games} Spiele, {wins} Siege. Der Bericht ist eindeutig.
- {wins} Siege. Die Liste bleibt im Amt.
- {games} Partien. Der Praxistest läuft.
- {wins} Siege. Der Ausschuss ist zufrieden.
- {games} Spiele, {wins} Siege. Keine weiteren Fragen.
- {wins} Siege. Das Deck bleibt vorerst zugelassen.
- {games} Partien. Der Gameplan wird noch geprüft.
- {wins} Siege. Der Antrag ist angenommen.

## app_data_intern — Interne Daten (Profil-Statistik)

Wo: Eigenes Profil, Statistik-Karte, kleine Zeile „Interne Daten“. {m} = durchschnittliche Minute des eigenen Ausscheidens, {victim} = Lieblingsopfer, {p} = Prozent Spiele ohne Sieg.

Platzhalter: {m} {victim} {p}

- Durchschnittlich {m} Minuten bis zum KO.
- Du wirfst am liebsten {victim} raus. Die Zahlen lügen nicht.
- {p} % deiner Spiele ohne Sieg. Interne Prüfung ergab: Shuffle.
- {p} % ohne Sieg. Die Auswertung läuft.
- Durchschnittlich {m} Minuten bis zur nächsten Ausrede.
- {p} % deiner Spiele: kontrollierter Kontrollverlust.
- Du hast {victim} öfter erwischt als den Kühlschrank.
- {p} % ohne Sieg. Die Theorie bleibt optimistisch.
- Im Schnitt {m} Minuten bis zur ersten Meinungsverschiedenheit.
- {p} % deiner Spiele enden anders als geplant.
- Durchschnittlich {m} Minuten bis zum ersten politischen Bündnis.
- {p} % ohne Sieg. Der Ausschuss tagt.
- Durchschnittlich {m} Minuten bis zur ersten Beschwerde.
- {p} % deiner Spiele enden mit offenen Fragen.
- Du hast {victim} öfter erwischt als den Einkaufszettel.
- {p} % ohne Sieg. Der Antrag wird vertagt.
- Im Schnitt {m} Minuten bis zur ersten Sitzungsunterbrechung.
- {p} % deiner Spiele enden ohne Einigung.
- Durchschnittlich {m} Minuten bis zur ersten Küchenpause.

## app_data_commander — Commander-Trivia

Wo: Kopf der Commander-Seite, ein Commander mit 3+ Spielen. {name} = wer ihn am häufigsten spielt ({k} Spiele, ab 2).

Platzhalter: {cmd} {games} {wins} {k} {name}

- {cmd} war {games}× am Tisch.
- {cmd} hat schon {wins} Siege. Keiner redet drüber.
- {cmd} wurde {games}× gespielt, davon {k}× von {name}.
- {cmd} war {games}× dabei. Niemand übernimmt Verantwortung.
- {cmd} hat {wins} Siege. Das bleibt unter uns.
- {cmd} wurde {games}× gespielt. Die Hütte urteilt.
- {name} hat {cmd} {k}× ins Feld geführt. Konsequenz.
- {cmd} war {games}× am Tisch. Die Meta notiert mit.
- {cmd} hat {wins} Siege. Das Deck weiß von nichts.
- {name} vertraut {cmd} seit {k} Partien. Mutig.
- {cmd} wurde {games}× gewählt. Alternativen gab es offenbar.
- {cmd} stand {games}× auf der Tagesordnung.
- {cmd} hat {wins} Siege. Der Ausschuss schweigt.
- {cmd} wurde {games}× gespielt. Die Akte ist eröffnet.
- {name} hat {cmd} {k}× eingesetzt. Das Protokoll notiert mit.
- {cmd} war {games}× dabei. Die Sitzung war lang.
- {cmd} hat {wins} Siege. Der Antrag gilt als angenommen.
- {name} setzt {cmd} seit {k} Partien ein. Konsequente Linie.
- {cmd} wurde {games}× gewählt. Die Alternativen bleiben unbekannt.

## app_data_report — Geekend-Bericht (nach Abschluss)

Wo: Seite eines abgeschlossenen Geekends, Block „Geekend-Bericht“: drei verschiedene Zeilen, fest pro Geekend. {e} = Name des Geekends, {champ} = Sieger, {killer} = meiste KOs, {victim} = am häufigsten raus, {quote} = ein Zitat aus den Erinnerungen.

Platzhalter: {e} {games} {kos} {selfko} {champ} {killer} {victim} {quote}

- {e}: {games} Spiele, {kos} KOs, {selfko} davon selbst verschuldet.
- Champion: {champ}. Größter Schaden: {killer}. Größtes Opfer: {victim}.
- Zitat des Wochenendes: {quote}
- {e}: {games} Spiele. Die Hütte braucht Erholung.
- {e}: {kos} KOs, {selfko} Selbsttreffer.
- Champion: {champ}. Die Einsprüche laufen.
- Zitat des Wochenendes: {quote} Keine weiteren Fragen.
- {e}: {games} Spiele, null gelöste Konflikte.
- Größter Schaden: {killer}. Größtes Fragezeichen: {victim}.
- {e}: {selfko} Selbst-KOs. Das Deck war’s.
- {champ} gewinnt. Die nächste Revanche ist bereits angekündigt.
- {e}: {games} Spiele. Die Akten sind geschlossen.
- {e}: {kos} KOs, {selfko} interne Vorgänge.
- Champion: {champ}. Der Ausschuss nimmt es zur Kenntnis.
- Zitat des Wochenendes: {quote} Die Sitzung ist vertagt.
- {e}: {games} Spiele, eine volle Tagesordnung.
- Größter Schaden: {killer}. Größter Erklärungsbedarf: {victim}.
- {e}: {selfko} Selbst-KOs. Die Prüfung läuft.
- {champ} gewinnt. Die nächste Sitzung ist bereits beantragt.
