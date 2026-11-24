# La méthode DOC · The DOC method

**FR** · La méthode DOC (Décisions, Ouverture, Clôture) est un cadre en trois fichiers et deux prompts, créé par Mamoun, pour qu'un projet mené avec une IA reprenne là où il s'est arrêté, d'une conversation à l'autre.

**EN** · The DOC method (Decisions, Opening, Closing) is a three-file, two-prompt framework, created by Mamoun, that lets a project run with an AI pick up where it left off, from one conversation to the next.

Site : [docmethod.org](https://docmethod.org/fr/)

## Ce que contient ce dépôt

- [`installateur/fr.txt`](installateur/fr.txt) : le prompt d'installation, en français. Tu le colles dans une conversation neuve avec ton IA ; elle t'installe le cadre en posant une question à la fois.
- [`installateur/en.txt`](installateur/en.txt) : the installation prompt, in English.
- [`installateur/es.txt`](installateur/es.txt) : el prompt de instalación, en español.

Version 0.5.1. En anglais et en espagnol, les fichiers gardent leurs noms anglais (`DECISIONS.md`, `OPENING.md`, `CLOSING.md`), pour que le sigle reste DOC.

## Le cadre en bref

- **Trois fichiers** : `DECISIONS.md` (ce qui est tranché, avec la date et la raison), `OUVERTURE.md` (où en est le projet, relu à chaque ouverture et réécrit à chaque clôture), `CLOTURE.md` (une entrée par séance, écrite à la clôture).
- **Deux prompts** : un pour ouvrir la séance (l'IA relit les fichiers et dit en cinq lignes où on en est), un pour la clôturer (l'IA met les fichiers à jour).
- **Testé sur** Claude et ChatGPT (disponibles), Gemini (en cours d'amélioration). Matrice datée : [docmethod.org/fr/teste-sur/](https://docmethod.org/fr/teste-sur/).

## Démarrer

1. Ouvre une conversation neuve avec ton IA (Claude, ChatGPT ou Gemini).
2. Colle le contenu de [`installateur/fr.txt`](installateur/fr.txt).
3. Réponds aux questions. À la fin, ton IA te dit où ranger les trois fichiers et les deux prompts.

Guides pas à pas : [Démarrer avec Claude](https://docmethod.org/fr/demarrer/claude/) · [Démarrer avec ChatGPT](https://docmethod.org/fr/demarrer/chatgpt/).

## Licence

[CC BY 4.0](LICENSE) : tu peux reprendre, adapter et intégrer le prompt et les textes, y compris dans un outil ou un produit, en citant la source : « La méthode DOC, Mamoun, docmethod.org ».

## Retours

Ce qui marche, ce qui casse, sur quel outil et quel modèle : les retours font évoluer la méthode. Ouvre une *issue* sur ce dépôt.
