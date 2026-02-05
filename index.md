# Politique de confidentialité — Zoom Web Double Ring (Sonnerie Zoom Phone)

Dernière mise à jour : 2026-02-05

## Résumé
L’extension "Zoom Web – Double Ring" ajoute une sonnerie supplémentaire sur les haut‑parleurs lors d’un appel entrant sur Zoom Web (app.zoom.us), tout en laissant la voix sur le casque (réglage audio géré dans Zoom).  
L’extension n’a pas vocation à collecter des données personnelles et fonctionne localement dans le navigateur.

## Données collectées
Aucune donnée personnelle n’est collectée, vendue ou transférée.

L’extension enregistre uniquement, dans le stockage local du navigateur (chrome.storage), des préférences techniques nécessaires au fonctionnement :
- le périphérique de sortie sélectionné pour la sonnerie (identifiant et/ou libellé du périphérique),
- des paramètres internes de fonctionnement (ex. indicateurs de test).

Ces informations restent locales au navigateur de l’utilisateur et ne sont pas envoyées à un serveur.

## Données consultées / traitées
Pour détecter un appel entrant, l’extension observe l’interface de Zoom Web sur les pages `https://app.zoom.us/*` et `https://*.zoom.us/*` afin d’identifier l’état « appel entrant » (présence d’éléments d’UI comme “Accepter / Refuser”).

L’extension ne lit pas le contenu des appels, n’enregistre pas la voix, et n’intercepte pas les flux audio WebRTC de Zoom.

## Utilisation des permissions
- storage : sauvegarder le périphérique HP sélectionné et quelques réglages.
- activeTab : permettre au popup de dialoguer avec l’onglet Zoom actif pour rafraîchir la liste des périphériques et effectuer un test.
- host permissions (zoom.us) : injecter le script de détection uniquement sur les pages Zoom pour identifier un appel entrant.

## Code distant / services tiers
L’extension n’exécute aucun code distant et ne dépend d’aucune API externe.  
Elle ne charge pas de scripts depuis Internet.

## Sécurité
Aucune donnée personnelle n’étant collectée, le risque lié au traitement de données est limité. Les préférences stockées localement peuvent être supprimées en réinitialisant les données de l’extension (Chrome → Extensions → Détails → “Effacer les données”).

## Contact
Pour toute question, vous pouvez contacter : support@it-telec.fr (ou votre contact IT habituel).

## Modifications
Cette politique pourra être mise à jour en cas d’évolution du produit. La date de mise à jour sera ajustée en conséquence.
