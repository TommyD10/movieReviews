# movieReviews
Info Site about movies

- box-shadow
- before, after
- background-size
- background-position
- visibility
- overflow
- overflow-wrap
- whitespace
- flex-box
- flex-flow
- SASS Mixins
- SASS import

- SCSS-Datei für Mixins, die in die Hauptdatei importiert wird
- Text-Shadow
- Box-Shadow
- Bonus: Media-Query für einspaltige Darstellung auf mobile

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
