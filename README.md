# PyQuiz
Dies ist ein Quiz mit Editor. Es funktioniert folgendermassen:<br/>
- Es gibt 2-4 Teams, die gegeneinander antreten.
- Das Spielfeld besteht aus einer Tabelle mit Fragen, die in Themenbereiche eingeteilt sind, ähnlich wie bei Jeopardy.
- Wenn ein Team an der Reihe ist, entscheidet es, welche Frage ausgewählt werden soll.
- Dann wird die Frage aufgedeckt und das Team hat Zeit, die Frage zu beantworten.
  - Ist die Antwort richtig, bekommt das Team die entsprechende Punktzahl gutgeschrieben und ist ein zweites Mal an der Reihe.<br/>
    Es sind zwei Fragen pro Team und Runde möglich.
  - Ist die Antwort falsch, werden dem Team die Punkte abgezogen und das nächste Team ist an der Reihe.
  - Sollte das Team aufgeben, ohne eine Antwort zu liefern, bleibt die Frage offen, ansonsten wird sie gestrichen.
- Das Spiel wird entweder beendet, wenn alle Fragen beantwortet sind, oder wenn der Spielleiter dies entscheidet.

Wie der Name sagt, ist das Quiz in Python programmiert, es basiert auf der tkinter-Oberfläche und funktioniert auf allen Betriebssystemen, die Python 3 unterstützen.
