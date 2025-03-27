# Documentation des Commandes prises en charges par le Bot Elaxer

Dernière mise à jour de ce document : 27/03/2025

## Introduction
Ce document liste et décrit les commandes disponibles pour le bot discord **Elaxer**.  
Des commandes peuvent être ajoutées, modifiées ou supprimées à tout moment.  
Les permissions requises pour certaines commandes peuvent également être ajustées selon les besoins.

### Commandes Administratives

**Bannir un membre**
- Permission : `Administrateur` ou `Bannir des membres`
- `/ban {member} [reason]`
  - `{member}` (discord.User) -> Membre à bannir
  - `[reason]` (str) -> Raison du bannissement

**Débannir un membre**
- Permission : `Administrateur` ou `Bannir des membres`
- `/unban {member} [reason]`
  - `{member}` (discord.User) -> Membre à débannir
  - `[reason]` (str) -> Raison du débannissement
 
**Expulser un membre**
- Permission : `Administrateur` ou `Expulser des membres`
- `/kick {member} [reason]`
  - `{member}` (discord.User) -> Membre à expulser
  - `[reason]` (str) -> Raison de l'expulsion

**Rendre muet un membre**
- Permission : `Administrateur` ou `Rendre muet un membre`

**Ne plus rendre muet un membre**
- Permission : `Administrateur` ou `Rendre muet un membre`

**Suppression de messages**
- Permission : `Administrateur` ou `Gérer les messages`
- `/clear {amount} [channel]`
  - `{amount}` (int) -> Nombre de messages à supprimer
  - `[channel]` (discord.TextChannel) -> Salon dans lequel les messages seront supprimés
 
**Avertir un membre**
- Permission : `NONE`

**Activer/Désactiver un système de Logs**
- `/logs {action} {id_channel}`
  - `{action}` (Literal\['activate','desactivate'\]) -> Action pour activer/désactiver les logs
  - `{id_channel}` (str) -> Salon dans lequel on veut afficher les logs

**Créer un Giveaway**
- `/giveaway {reward} {duree} {unite}`
  - `{reward}` (str) -> Récompense du Giveaway
  - `{duree}` (int) -> Durée du Giveaway
  - `{unite}` (Literal\['seconde','minute','heure','jour'\]) -> Unité de la durée

**Obtenir un rôle via des réactions**
- `/reactionrole {emoji} {role_id} {message_link}`
  - `{emoji}` (str) -> Emoji de la réaction
  - `{role_id}` (str) -> Identifiant du rôle
  - `{message_link}` (str) -> Lien du message

## Commandes d'Information

**Informations sur un membre**
- `/user_info {member}`
  - `{member}` (discord.Member) -> Membre sur lequel on souhaite des informations

**Informations sur un serveur**
- `/server_info`

## Commandes Fun

**Générer un QRCode via une URL**
- `/qrcode {URL} [bg_color] [box_color] [box_size] [border_size]`
  - `{URL}` (str) -> Lien qui sera mis sous forme de QRCode
  - `[bg_color]` (Literal\['white','black','red','blue','green'\]) -> Couleur du fond de QRCode
  - `[box_color]` (Literal\['white','black','red','blue','green'\]) -> Couleur du QRCode
  - `[box_size]` (int) -> Taille du QRCode
  - `[border_size]` (int) -> Taille de la bordure du QRCode

**Remplacer des caractères par des caractères similaires**
- `/chinese {text}`
  - `{text}` (str) -> Texte à changer avec des caractères similaires

**Une petite blague**
- `/blague`

**Un petit proverbe**
- `/proverbe`

**Trouve le chat caché**
- `/jeu`

**Une blague d'humour noir**
- `/humour_noir`

**Une petite histoire**
- `/histoire`

**Un petit proverbe spécial développeur**
- `/dev`

**Quelques liens à propos de moi**
- `/alexer`

**Joue au puissance 4**
- `/puissance4 {adversaire}`
  - `{adversaire}` (discord.Member) -> Adversaire de jeu

**Joue au pendu (SOLO)**
- `/pendu`

**Joue au pendu (AVEC UN AMI)**
- `/pendu_ami {adversaire}`
  - `{adversaire}` (discord.Member) -> Adversaire de jeu

**Joue au morpion**
- `/morpion {adversaire}`
  - `{adversaire}` (discord.Member) -> Adversaire de jeu

**Joue au blackjack**
- `/blackjack`

**Créer un serveur entier**
- `/create_serveur`

---
**Note:** Certaines commandes nécessitent des permissions spécifiques pour être exécutées.


> Un bug ? Ajoutez moi sur Discord : `.alexer`
