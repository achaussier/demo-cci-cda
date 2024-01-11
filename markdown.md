# Cours Markdown

## Formatage du texte

On peut faire **du gras**, de *l'italique*, ~~du barré~~ et <span style="text-decoration: underline;">en rusant du souligné</span>.

On peut gérer du code, soit inline, comme pour `ls -la` , soit en bloc:

```html
<html>
  <head>
  </head>
  <body>
    <h1>Text</h1>
  </body>
</html>
```
Exemple ligne 1.
Toujours ligne 1.

Ligne 2

> Petits commit, petites emmerdes !
> Toujours ligne 1
>
> Ligne 2

## Les liens

[Github](https://github.com)

[Tout en haut](#cours-markdown)

[Autre doc](./pwet.md)

## Les listes

1. Elem 1
2. Elem 2
   1. Sous elem 1

- Elem 1
- Elem 2
  - Pwet

## Les images

![Tux rambo](https://external-content.duckduckgo.com/iu/?u=http%3A%2F%2Fcrevette63410.c.r.pic.centerblog.net%2Fdogg4il3.png&f=1&nofb=1&ipt=01685c176294dd5812929d4ec524ca4b0e844bfd92859b253e329c4743a12c8d&ipo=images)
![Gandalf](./images/tux.jpg)

## Les tableaux

| Nom de commande | Description |
| --- | --- |
| `ls` | Liste les fichiers |
| `cat` | Affiche un contenu |