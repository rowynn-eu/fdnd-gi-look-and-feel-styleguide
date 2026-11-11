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

Een class noem je eerst het HTML element, en daarna wat het is.

bijvoorbeeld. 

```css

.button-menu {
/* je code hier */
}

.input-search {
/* je code hier */
}

.a-link {
/* je code hier */
}

.a-cta-button {
/* je code hier */
}

```

### Comments
Als je een comment ga toevoegen aan het stylesheet, probeer comments op zulke manier toe tevoegen. Indien nodig, kan je "MARK:" toevoegen aan het begin.
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
## Licentie

This project is licensed under the terms of the [MIT license](./LICENSE).

