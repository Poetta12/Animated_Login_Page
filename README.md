# Animated Login Page

## Description

**Animated Login Page** est un projet de page de connexion développée avec **HTML** et **CSS**. Cette page présente un design moderne et élégant, mettant en avant des animations pour les champs de saisie.

## Fonctionnalités Principales

- **Champs de saisie animés** : Les éléments de saisie offrent des effets d'animation lors de l'interaction.

## Détails du Fonctionnement du Code

### HTML

Le fichier `index.html` contient la structure de la page de connexion, incluant :

- **Formulaire de connexion** : Avec des champs pour le nom d'utilisateur et le mot de passe.
- **Liens supplémentaires** : Pour la récupération de mot de passe et l'inscription.

#### Extrait HTML principal :

```html
<div class="holder">
    <div class="box">
        <form autocomplete="off">
            <h2>Sign in</h2>
            <div class="inputBox">
                <input type="text" required="required">
                <span>Username</span>
                <i></i>
            </div>
            <div class="inputBox">
                <input type="password" required="required">
                <span>Password</span>
                <i></i>
            </div>
            <div class="links">
                <a href="#">Forgot Password?</a>
                <a href="#">Signup</a>
            </div>
            <input type="submit" value="Login">
        </form>
    </div>
</div>
```
### CSS

Le fichier `style.css` gère l'apparence visuelle de la page, notamment :

- **Centrage et mise en page** : Utilisation de Flexbox pour aligner les éléments.
- **Effets de transition** : Les champs de saisie ont des animations lors de l'interaction.

```
body {
    background: url("/sand.jpeg") no-repeat center center;
    background-size: cover;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    flex-direction: column;
}
```
### Concepts Utilisés

- **Flexbox pour la disposition** : Assure que le contenu soit centré sur la page.
- **Transitions CSS** : Utilisées pour rendre les interactions plus engageantes.

### Fichiers du Projet

- `index.html` : Structure de la page de connexion.
- `style.css` : Style et animations de la page.

### Guide d'Utilisation

- **Interagir avec le formulaire** : Remplissez les champs pour voir les animations.

### Fonctionnalités Supplémentaires Possibles

- **JavaScript pour des interactions avancées** : Ajouter des fonctionnalités comme des messages d'erreur ou une validation de formulaire.
- **Optimisation Mobile** : Ajouter des media queries pour améliorer l'expérience sur mobile.

### Contribution

Les contributions sont les bienvenues ! Si vous souhaitez améliorer ce projet ou ajouter de nouvelles fonctionnalités, vous pouvez :

1. Faire un fork de ce dépôt.
2. Créer une nouvelle branche (`git checkout -b feature/nouvelle-fonctionnalite`).
3. Soumettre vos modifications (`git commit -m 'Ajouter nouvelle fonctionnalité'`).
4. Pousser la branche (`git push origin feature/nouvelle-fonctionnalite`).
5. Ouvrir une Pull Request.

### Licence

Ce projet est sous licence MIT. Pour plus d'informations, consultez le fichier [LICENSE](LICENSE).

### Auteur

**Pedro Costa**  
[LinkedIn](https://linkedin.com/in/pedronfcosta/)



