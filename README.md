---

# Bagels - Jeu de Déduction Logique

## Description

**Bagels** est un jeu de déduction logique où vous devez deviner un nombre secret à trois chiffres.  
Après chaque tentative, vous recevez des indices pour vous aider à trouver la bonne réponse :  

- **Fermi** : Un chiffre est correct et bien placé.
- **Pico** : Un chiffre est correct mais mal placé.
- **Bagels** : Aucun chiffre n'est correct.

Vous avez **10 essais** pour deviner le nombre secret.

## Auteur

- **Nom** : ADEBI Ayedoun Châ-Fine  
- **Email** : achafine@gmail.com  
- **Date** : 16 mars 2025  

## Prérequis

Ce jeu fonctionne avec **Python 3**. Assurez-vous d'avoir Python installé sur votre machine.

## Installation

Aucune installation spécifique n'est requise. Clonez simplement ce dépôt et exécutez le script :

```bash
git clone https://github.com/votre-repo/bagels.git
cd bagels
python3 bagels.py
```

## Comment jouer ?

1. Lancez le script `bagels.py` avec Python 3.
2. Un nombre secret à 3 chiffres est généré.
3. Entrez un nombre à trois chiffres pour essayer de le deviner.
4. Recevez des indices :
   - **Fermi** : chiffre correct à la bonne position.
   - **Pico** : chiffre correct mais mauvaise position.
   - **Bagels** : aucun chiffre correct.
5. Vous avez **10 essais** pour trouver le bon nombre.
6. À la fin, vous pouvez rejouer ou quitter.

## Exécution

Pour lancer le jeu, utilisez :

```bash
python3 bagels.py
```

## Exemple de partie

```
Bagels, a deductive logic game.
By ADEBI Ayedoun Châ-Fine achafine@gmail.com

Je suis en train de penser à un nombre à 3 chiffres.
Essayez de deviner lequel.

Devine #1
> 123
Pico

Devine #2
> 456
Bagels

Devine #3
> 789
Fermi Pico

[...]

Vous l'avez trouvé !
Voulez-vous encore jouer ?? (oui ou non)
> non

Merci d'avoir joué !
```

## Améliorations possibles

- Ajout d'un mode **difficulté** avec plus de chiffres.
- Interface graphique avec **Tkinter** ou **Pygame**.
- Ajout d'un mode **multijoueur**.

---
