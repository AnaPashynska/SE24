# SE24
Hausaufgabe für Software Engineering — Wintersemester 2024
Beschreibung
Dieses Repository enthält die Lösung der Hausaufgabe für den Kurs Software Engineering im Wintersemester 2024. Die Aufgabe wurde in Java implementiert und verwendet JUnit für Unit-Tests. Das Repository umfasst die wesentlichen Klassen zur Umsetzung einer Übersetzungsfunktion für Zahlen ins Deutsche sowie deren Tests.

Projektstruktur
├── src
│   └── org.hbrs.se1.ws24.exercises
│       ├── uebung1
│       │   └── control
│       │       ├── GermanTranslator.java
│       │       ├── Translator.java
│       │       └── TranslatorFactory.java
│       └── view
│           └── Client.java
└── test
    └── org.hbrs.se1.ws24.tests.uebung1
        └── GermanTranslatorTest.java
src/ — Hauptordner des Quellcodes.

control/ — enthält Klassen zur Implementierung der Übersetzungslogik.
GermanTranslator.java — Klasse, die die Übersetzung von Zahlen ins Deutsche realisiert.
Translator.java — Schnittstelle für verschiedene Übersetzungsimplementierungen.
TranslatorFactory.java — Fabrik zur Erstellung von Übersetzungsinstanzen.
view/ — enthält die Client-Klasse Client.java, die die Nutzung des Übersetzers demonstriert.
test/ — Ordner für die Tests, enthält Tests zur Überprüfung der Programmfunktionalität.

GermanTranslatorTest.java — Testklasse zur Überprüfung der Funktionalität des GermanTranslator mithilfe von JUnit.
