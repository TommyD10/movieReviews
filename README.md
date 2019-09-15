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
@mixin reset-list {
  margin: 0;
  padding: 0;
  list-style: none;
}
```
###### Mixin verwenden
```scss
@include reset-list
```
