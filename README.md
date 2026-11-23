# Prélèvements

Gestion des prélèvements façon CRM : comptes, personnes, synthèse mensuelle avec cartes, vue annuelle.

- Application : https://graziosojulien2.github.io/prelevements/
- Connexion Google réservée à un seul compte, données dans Firebase Firestore (projet `prelevements-869b7`).
- `firestore.rules` : règles de sécurité appliquées à la base (copie de référence).
- Aucune donnée personnelle (IBAN, montants…) n'est stockée dans ce dépôt : tout est dans la base, derrière la connexion.
