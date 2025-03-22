# NOTES

## GENERAL
- Le **frontmatter**, c'et lapartie en haut du fichier .MD (en YAML) ou .astro (en JS ou TS) 

## SYNTAXE MD
- italique : _new blog_

## .ASTRO
- Dans le frontamatter, on écrit des expressions JS ou TS et on pourra utiliser les variables définies dedans dans le HTML en les nommant entre {}.
- On peut utiliser du JS/TS entre les {} dans la partie HTML du fichier .astro, comme en JSX par exemple `map()` ou encore les opérateurs logiques pour le rendu conditionnel comme avec `&&`, les ternaires etc....

## STYLE
- Une méthode est de :
1. Créer un global.css pour le site qu'on importera via le frontmatter du .astro
2. Appliquer le style particulier à la page.astro via des balises `<style></style>` dans le `<head>` du .astro
- CSS variable définie dans le frontmatter du .astro réutilisable avec `var(--maVariable)`.


