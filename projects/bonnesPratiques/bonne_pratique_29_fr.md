## Favoriser les polices standards

### Alternatives

Via les préférences de leurs navigateurs, vos utilisateurs peuvent faire le choix de demander d'optimiser les requêtes réseau réalisées pour les sites qu'ils visitent. À l'aide d'une media query, la font n'est alors téléchargée que pour les utilisateurs la souhaitant.  

Dans l'exemple ci-dessous, nous ne téléchargeons que la font `Montserrat` si et seulement si l'utilisateur n'a pas défini de préférence. Si ce n'est pas le cas, la font ne sera pas téléchargée, et la font `Arial` sera utilisée.  

```css
@media (prefers-reduced-data: no-preference) {
    @font-face {
        font-family: Montserrat;
        font-style: normal;
        font-weight: 400;
        src:  url('fonts/montserrat-regular.woff2');
    }
}

body {
  font-family: Montserrat, Arial, sans-serif;
}
```

Nous pouvons par exemple aussi utiliser ce principe pour : 
* décharger une image optimisée
* désactiver le chargement dynamique automatique d'une liste de données

Pour plus d'informations sur la media query `prefers-reduced-data`, vous pouvez retrouver l'article dédié sur le site [MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/@media/prefers-reduced-data)
