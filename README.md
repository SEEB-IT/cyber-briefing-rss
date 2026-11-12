# Briefing cybersécurité — flux RSS & affichage dynamique

Veille hebdomadaire de cybersécurité (France & monde), publiée sous deux formats :

| Fichier | Contenu | URL publique |
|---|---|---|
| `feed.xml` | Flux RSS 2.0 (UTF-8) — un nouvel `<item>` par semaine | `https://raw.githubusercontent.com/SEEB-IT/cyber-briefing-rss/main/feed.xml` |
| `briefing.html` | Page plein écran 16:9 pour écran dynamique / kiosque | `https://seeb-it.github.io/cyber-briefing-rss/briefing.html` |
| `seeb-image.jpg` | Illustration facultative du thème de la semaine (référencée par la page) | `https://raw.githubusercontent.com/SEEB-IT/cyber-briefing-rss/main/seeb-image.jpg` |

## Contenu du briefing

Chaque semaine, la veille couvre en priorité :

- Les recommandations et alertes de l'**ANSSI** (cyber.gouv.fr)
- Les publications et alertes de **cybermalveillance.gouv.fr**
- Les avis et rapports du **CERT-FR** (cert.ssi.gouv.fr)
- Les grandes actualités mondiales de la cybersécurité

## S'abonner au flux RSS

Copier l'URL de `feed.xml` dans votre agrégateur (Feedly, Thunderbird, Outlook, FreshRSS…) — le flux conserve l'historique des semaines précédentes.

## Afficher la page sur un écran

La page `briefing.html` est conçue pour un affichage permanent sur écran large (16:9) :

- 4 volets en rotation automatique (thème de la semaine → France → international → points clés)
- Horloge et date en direct
- Illustration du thème (masquée automatiquement si absente)
- Aucune interaction requise — idéale pour un navigateur en mode kiosque

## Mise à jour

Le contenu est régénéré et publié **automatiquement chaque lundi matin** ; aucune intervention manuelle n'est nécessaire. Les fichiers de ce dépôt sont la destination finale d'une chaîne de publication interne.

## Sources

Institutions : [ANSSI](https://cyber.gouv.fr) · [CERT-FR](https://cert.ssi.gouv.fr) · [cybermalveillance.gouv.fr](https://cybermalveillance.gouv.fr)
Presse : AFP, AP et sources citées dans chaque item du flux.
