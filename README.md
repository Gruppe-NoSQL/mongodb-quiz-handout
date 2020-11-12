# Gruppe 'NoSQL'-Handout

#### Spaltendatenbanken:
- Tabellen werden in Spalten aufgeteilt mit Zeilennummern je Eintrag
- Spalten werden in Spaltenfamilien (column families) gruppiert
- Spalten werden mit run-length-Einteilung speicheroptimiert

##### Codebeispiele:
- Aggregate, wie die Summe einer Spalte einfach und schnell:
```
SELECT SUM(columnName) FROM tableName;
```

- Änderungen ganzer Spalteneinträge ebeso:
```
UPDATE tableName SET columnName = columnName * 1.03;
```

#### Gruppenmitglieder
- Robin Reyer | 1275865
- Maik Kebernik | 6172455
- Fynn Weyrich | 9818779

#### Links zu unseren Repositories und Aufteilung der Arbeit:
 - [Frontend](https://github.com/Gruppe-NoSQL/mongodb-quiz-frontend) - Matthias, Maik, Fynn
 - [Backend](https://github.com/Gruppe-NoSQL/mongodb-quiz-backend) - Robin, Florian, Fynn
 - [Hosting](https://github.com/Gruppe-NoSQL/mongodb-quiz-hosting) - Fynn