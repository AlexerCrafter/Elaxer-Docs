# Documentation des Commandes du Bot Discord

## Introduction
Ce document liste et décrit les commandes disponibles pour le bot Discord de Alexer.

## Commandes Administratives

### `/ban`
**Description:** Bannir un membre du serveur.
**Permissions:** Administrateur ou permission de bannir des membres.
**Arguments:**
- `member` : Membre à bannir.
- `reason` : Raison du bannissement (optionnelle).

### `/unban`
**Description:** Débannir un membre du serveur.
**Permissions:** Administrateur ou permission de bannir des membres.
**Arguments:**
- `member` : Membre à débannir.
- `reason` : Raison du débannissement (optionnelle).

### `/kick`
**Description:** Expulser un membre du serveur.
**Permissions:** Administrateur ou permission d'expulser des membres.
**Arguments:**
- `member` : Membre à expulser.
- `reason` : Raison de l'expulsion (optionnelle).

### `/mute`
**Description:** Rendre muet un membre pour une durée définie.
**Permissions:** Administrateur ou permission de rendre muet un membre.
**Arguments:**
- `member` : Membre à mute.
- `temps` : Durée du mute.
- `unité` : Unité de temps (sec, min, h).
- `reason` : Raison du mute (optionnelle).

### `/clear`
**Description:** Supprimer un certain nombre de messages dans un canal.
**Permissions:** Administrateur ou permission de gérer les messages.
**Arguments:**
- `amount` : Nombre de messages à supprimer.
- `channel` : Salon où supprimer les messages (optionnel).

## Commandes d'Information

### `/user_info`
**Description:** Obtenir des informations sur un utilisateur.
**Arguments:**
- `member` : Membre à analyser.

### `/server_info`
**Description:** Obtenir des informations sur le serveur.

## Commandes Fun

### `/qrcode`
**Description:** Générer un QR code.
**Arguments:**
- `url` : Lien à transformer en QR code.
- `bg_color` : Couleur du fond.
- `box_color` : Couleur des cases.
- `box_size` : Taille des cases.
- `border_size` : Taille de la bordure.

### `/blague`
**Description:** Afficher une blague aléatoire.

### `/proverbe`
**Description:** Afficher un proverbe aléatoire.

### `/jeu`
**Description:** Trouver le chat caché.

### `/humour_noir`
**Description:** Afficher une blague d'humour noir.

### `/histoire`
**Description:** Afficher une histoire drôle.

## Commandes de Jeux

### `/tetris`
**Description:** Jouer à Tetris sur Discord.

### `/puissance4`
**Description:** Lancer une partie de Puissance 4.
**Arguments:**
- `adversaire` : Joueur adverse.

### `/play_p4`
**Description:** Jouer un coup au Puissance 4.
**Arguments:**
- `column` : Numéro de la colonne où placer son jeton.

### `/pendu`
**Description:** Jouer au Pendu.

### `/deviner`
**Description:** Deviner une lettre pour le jeu du Pendu.
**Arguments:**
- `letter` : Lettre à deviner.

## Commandes Diverses

### `/alexer`
**Description:** Obtenir des liens vers les réseaux sociaux du créateur.

### `/sondage`
**Description:** Créer un sondage avec un compte à rebours.
**Arguments:**
- `question` : Question du sondage.
- `options` : Réponses possibles (séparées par une virgule).
- `duration` : Durée du sondage en secondes.

## Commandes Spéciales

### `/dieu`
**Description:** Bannir un membre avec la Grâce Divine de Dieu.
**Permissions:** Uniquement Alexer.

### `/cacaor`
**Description:** Bannir un membre avec Cacaor.
**Permissions:** Uniquement Emma.

### `/chatiment`
**Description:** Bannir un membre avec le Châtiment des Enfers.
**Permissions:** Uniquement Erased.

---

**Note:** Certaines commandes nécessitent des permissions spécifiques pour être exécutées.
