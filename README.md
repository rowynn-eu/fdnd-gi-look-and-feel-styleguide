# Styleguide Gemeenteniconen.nl

Dit is een gedeelde stylesheet die we gaan gebruiken voor onze opdracht voor OpenGemeente.

Leden: @rowynn-eu, @melis5016, @celeste0012, @samielb

## File Structuur / Code Conventions:

Probeer aan deze code conventie te houden voor het CSS bestand.

### Naam conventie voor properties

Als je een custom property toevoeg, zoals voor onze design tokens, dan zien ze er zo eruit.

```css

html {

/* fg staat voor foreground, bg voor backrgound */
--fg-0: light-dark(#333, #fff)
--bg-0: light-dark(#fff, #333)

}

```


### BEM-like CSS

Class properties krijgen geen ``--`` aan het begin om ze te onderscheiden.

Simpele class selectors:
```css
.--button-menu {
padding: var(--spacing-m);
}

```

Nested HTML selectors:

```css
.--button__menu-logo {
background-image: url('....');
]
```


### Comments
Probeer de volgende comments te gebruiken tussen componenten met 1 regel witruimte.
```css

/*********/
/* TITLE */
/*********/

```
## Licentie

This project is licensed under the terms of the [MIT license](./LICENSE).

