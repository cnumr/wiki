## Préférer la saisie assistée à l'autocomplétion

### Alternatives

* Utilisation de l'élément HTML [datalist](https://developer.mozilla.org/fr/docs/Web/HTML/Element/datalist)

Si la quantité de données proposée à l'utilisateur est raisonnable, vous pouvez l'inclure directement dans votre code HTML en utilisant l'élément `datalist`. Ce système proposera nativement, et sans aller-retour avec le serveur, un mécanisme d'autocomplétion.

```html
<label for="ice-cream-choice">Choose a flavor:</label>
<input list="ice-cream-flavors" id="ice-cream-choice" name="ice-cream-choice" />

<datalist id="ice-cream-flavors">
    <option value="Chocolate">
    <option value="Coconut">
    <option value="Mint">
    <option value="Strawberry">
    <option value="Vanilla">
</datalist>
```
