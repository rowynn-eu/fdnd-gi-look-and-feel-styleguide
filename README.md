# Styleguide Gemeenteniconen.nl

Dit is een gedeelde stylesheet die we gaan gebruiken voor onze opdracht voor OpenGemeente.

Leden: @rowynn-eu, @melis5016, @celeste0012, @samielb

## File Structuur / Code Conventions:

Probeer aan deze code conventie te houden voor het CSS bestand.

### Naam conventie voor properties

Als je een custom property toevoeg, zoals voor onze design tokens, dan zien ze er zo eruit, met een `--` als prefix, en `-` voor een spatie.

```css

html {

/* fg staat voor foreground, bg voor backrgound */
--fg-0: light-dark(#333, #fff);
--bg-0: light-dark(#fff, #333);

}

```


### Class selectors

[BEM](https://bem.info/en/methodology/css/) is ingewikkeld. Een class noem je eerst het HTML element, en daarna wat voor functie het heeft.

bijvoorbeeld. 

```css

.input-search {
/* je code hier */
}

.input-radio {
/* je code hier */
}

.input-select {
/* je code hier */
}

.input-option {
/* je code hier */
}


.h1 {
/* je code hier */
}

.h2 {
/* je code hier */
}

.h3 {
/* je code hier */
}

```

### Comments
Als je een comment ga toevoegen aan het stylesheet boven aan een hoop code, probeer comments op zulke manier toe tevoegen. Indien nodig, kan je "MARK:" toevoegen aan het begin.

Dit kan je een 'footmark noemen'.
```css

/*********/
/* TITLE */
/*********/

```

```css

/***************/
/* MARK: TITLE */
/***************/

```

Als je in-line comments wil gebruiken, hoef je geen visueel marker te gebruiken voor overzichtelijkheid. Dat kan je gewoon laten zoals in de vorige voorbeelden.

## Licentie

This project is licensed under the terms of the [MIT license](./LICENSE).

