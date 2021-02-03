# portfolio-challenge

## Bienvenue! 👋

**Pour dévelper votre portfolio, vous avez besoin d'une compréhension de base du HTML et du CSS.**

## Où tout trouver?

Votre tâche consiste à construire le projet from scratch.
Mettez vos images utilisés dans :file_folder: `/assets`. Vous y trouverez les fichiers html sur laquelle travailler.

Réalisez les maquettes en format JPG, PDF ou bien en XD. Nommez les maquettes comme cet exemple: *Portfolio-low-fed.pdf* , *Portfolio-high-fed.xd*. Mettez vos maquettes réaliser dans :file_folder: `/mockup`.

Il existe également un fichier 'style-guide.md', remplir ce fichier par les informations dont vous aurez utilisés, telles que la palette de couleurs et les polices.

## Construire votre projet

N'hésitez pas à utiliser le flux de travail qui vous convient le mieux. Vous trouverez ci-dessous une suggestion de procédure, mais n'estimez pas nécessaire de suivre ces étapes :

1. Initialisez votre projet en tant que dépôt public sur [GitHub](https://github.com/).
2. Configurez votre 'repository' pour publier votre code dans un URL. I existe plusieurs méthode de procéder, mais je recommande d'utiliser [Vercel](https://bit.ly/fem-vercel).
3. Faire un brainstorming sur les portfolios qui existent déjà sur le Net.
4. Examinez les modèles créés pour commencer à planifier la manière dont vous allez aborder le projet. Cette étape est cruciale pour vous aider à anticiper les classes CSS que vous pourriez créer pour créer des styles réutilisables.
5. Ajoutez CDN de [AnimateCSS](https://animate.style/).
```html
<head>
  <link
    rel="stylesheet"
    href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"
  />
</head>
```

6. Avant d'ajouter des styles, structurez votre contenu avec du HTML. Le fait d'écrire d'abord votre HTML peut vous aider à vous concentrer sur la création d'un contenu bien structuré,

```
.
├── index.html          # La première page de votre portfolio
│   ├── Menu            # Navigation sur les pages (index, skills, portfolio, contact)
│   ├── Hero section    # Grand titre, Image, button redirige vers votre CV
│   └── footer          # Copyright + social icons
├── skills.html         # La deuxième page de votre portfolio
│   ├── Menu            # Navigation sur les pages (index, skills, portfolio, contact)
│   ├── About           # Sommaire (paragraphe)
│   ├── Compétences     # Décrivez les technos que vous maîtrisez (animation est importante)
│   └── footer          # Copyright + social icons
├── project.html        # La troisième page de votre portfolio
│   ├── Menu            # Navigation sur les pages (index, skills, portfolio, contact)
│   ├── Projects        # Cards (image, title, description, button redirige vers le projet)
│   └── footer          # Copyright + social icons
└── contact.html         # La quatrième page de votre portfolio
    ├── Menu            # Navigation sur les pages (index, skills, portfolio, contact)
    ├── formulaire      # (Nom complet, Email, Message, button d'envoie)
    └── footer          # Copyright + social icons
```

7. Rédigez les styles de base pour votre projet, y compris les styles de contenu général, tels que :pencil2: `font-family` et `font-size`.
8. Commencez à ajouter des styles en haut de la page et travaillez en bas. Ne passez à la section suivante que lorsque vous êtes satisfait d'avoir terminé le domaine sur lequel vous travaillez.
9. Les commentaires sont évidents :pushpin:

## Déployez votre projet

Comme mentionné ci-dessus, il existe plusieurs façons d'héberger gratuitement votre projet. Je vous recommande d'utiliser [Vercel](https://bit.ly/fem-vercel) c'est un service incroyable et extrêmement simple à mettre en place. Si vous souhaitez utiliser Vercel, voici quelques étapes à suivre pour commencer: 

1. [Sign up to Vercel](https://bit.ly/fem-vercel-signup) et suivez le processus d'intégration, en vous assurant que votre compte GitHub est connecté en utilisant leur [Vercel pour GitHub](https://vercel.com/docs/v2/git-integrations/vercel-for-github) integration.
2. Connectez votre projet à Vercel depuis la [page "Import project"](https://vercel.com/import), using the "From Git Repository" button and selecting the project you want to deploy.
3. Une fois connecté, à chaque fois que vous `git push`, Vercel créera un nouveau [deployment](https://vercel.com/docs/v2/platform/deployments) et l'URL de déploiement sera affichée sur votre [Dashboard](https://vercel.com/dashboard). Vous recevrez également un e-mail pour chaque déploiement avec l'URL.

## Partagez votre solution

Vous devez partager votre solution à plusieurs endroits:

1. Soumettez-le sur la plateforme. ["Simplonline"](https://simplonline.co/briefs/421b6cde-ce37-4e27-a37e-3d22bbbaf18b) pour soumettre le rendu.
2. Partagez votre solution **#i-made-this** channel sur discord [Discord community](https://discord.com/channels/796004789359476736/797776487998685214).

**Best of luck Coding Guild!** 🚀
