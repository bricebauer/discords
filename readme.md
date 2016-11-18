# Theme Discords

télécharger le ficheir se trouvant [ici](https://github.com/bricebauer/discords/blob/master/superman.theme.css)

ceci est un fichier exemple.

```css
modifier la ligne //META{"name":"Superman","description":"Superman themes","author":"Brice","version":"1.0"}*//
pour inscrire votre propre description / author / version
```

```css
modifier la ligne 
body:before {
    content: "template";
    ....
    }
    
pour mettre dans content, votre description.

```

pour les images, n'importe quelle format (jpg ou png, osef de la taille tant que c'est grand)

idéalement stocké l'image sur http://imgur.com

pour le lien des images, il faut faire les liens avec le protocol https (je sais pas pkoi mais en http, ça passe pas)

le fichier doit se nommer suivant ce schema : <nomen minuscule sans espace>.theme.css et placer dans le répertoire theme