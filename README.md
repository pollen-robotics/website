# Pollen Robotics Website


Pour les utilisateurs MacOS, le plus simple est de passer par homebrew. Ouvrez un terminal et faites un 

```bash
brew install hugo
```

Si vous n'avez pas homebrew d'installé, il faut le faire suivant cette procédure très simple [https://brew.sh/index_fr](https://brew.sh/index_fr)

Vous pouvez ensuite télécharger le site sur votre ordinateur avec git (si vous n'avez pas git ⇒ brew install git):

```bash
git clone https://github.com/pollen-robotics/website.git
```

Ensuite allez dans le dossier et lancez hugo pour générer le site sur votre ordinateur:

```bash
hugo server -D
```

- L'option server sert à lancer un serveur local qui va vous permettre de voir le site à l'adresse [http://localhost:1313/](http://localhost:1313/)
- L'option -D permet de régénérer automatiquement le site à chaque fois que vous faites une modification dans son contenu.