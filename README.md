# Radar B2B — prospection B2B par mots-clés

App Android installable (PWA) : vous tapez des mots-clés et une zone, l'app trouve les entreprises cibles (acheteurs, fournisseurs, distributeurs…), leurs coordonnées et décideurs, les range dans un pipeline et rédige vos messages e-mail / WhatsApp.

**URL** : https://eldo81.github.io/radar-b2b/

## Installer sur Android
1. Ouvrir l'URL dans **Chrome** (pas depuis le navigateur intégré de WhatsApp ou Gmail).
2. Menu ⋮ → **Installer et créer un raccourci** → **Installer**.
3. Ouvrir l'app depuis l'icône Radar B2B, puis **Réglages** : clé OpenAI (reprise automatiquement de Traducteur Live si déjà saisie), profil et offre.

## Fonctions
| Onglet | Fonction |
|---|---|
| **Rechercher** | Mots-clés (plusieurs séparés par virgule), zone, cible, 10/20/30 résultats. Liens directs Google Maps, LinkedIn, Kompass, Europages, Go Africa Online, Alibaba. |
| **Leads** | Score 0-100, décideur, e-mail, téléphone. Appeler, WhatsApp, E-mail, Message IA (e-mail + WhatsApp + relance J+4), LinkedIn, source. Statuts Nouveau → Client / Perdu, favoris, notes, filtres, export CSV. |
| **Veilles** | Recherches enregistrées, relance en 1 tap, seules les nouvelles entreprises s'ajoutent. |
| **Réglages** | Clé API, modèle, profil expéditeur, sauvegarde / restauration JSON. |

## Sources
- **IA + recherche web** : OpenAI Responses API avec l'outil `web_search`. Aucun contact inventé, URL source obligatoire. 30 à 120 s par recherche.
- **OpenStreetMap** : gratuit, sans clé ; surtout établissements physiques, rarement des e-mails.

## Limites
Données stockées sur le téléphone uniquement : exportez le CSV ou la sauvegarde JSON régulièrement. Vérifiez un contact via le lien « Source » avant un envoi important. Pas de scraping LinkedIn : l'app ouvre la recherche LinkedIn pré-remplie.

## APK / Play Store
pwabuilder.com → coller l'URL → *Package for stores* → Android : APK/AAB signé (Trusted Web Activity).
