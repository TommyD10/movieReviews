# movieReviews
Info Site about movies

- box-shadow
- before, after
- background-size
- background-position
- visibility


- SCSS-Datei für **Mixin**s, die in die Hauptdatei **import**iert wird
- **SASS-Variablen** für Farben und Breakpoints benutzen
- **Text-Shadow** für Hauptüberschrift
- **Box-Shadow** für Container mit Hauptinhalt
- Aufteilung der Bereiche mit **flex-box**
- Scrollleiste mit **overflow: scroll** oder **overflow: auto**
- In Menü-Elementen zu lange Texte mit **overflow: hidden** abschneiden
- In Menü-Elementen Worttrennung mit **whitespace** und **overflow-wrap** kontrollieren
- Bonus: **Media-Query** für einspaltige Darstellung auf mobile

- kein float benutzen

###### Mixin definieren
```scss
@mixin name {
  property: value;
}
```
###### Mixin verwenden
```scss
@include reset-list
```
###### Mixin mit parametern
```scss
@mixin name($parameter) {
  property: $parameter;
}
```
###### Mixin mit parametern verwenden
```scss
@include name(value)
```
###### Scrollleiste hinzufügen
```css
overflow: scroll;
```
###### Überstehenden Inhalt abschneiden
```css
overflow: hidden;
```
###### Nur wenn Inhalt größer als Container, Scrollleiste anzeigen
```css
overflow: auto;
```
