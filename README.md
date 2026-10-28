# Formulaire de contact SvelteKit

Un formulaire dont les messages arrivent par courriel.

Modèle de départ Bastide (`formulaire-contact-sveltekit`), écrit par Glowsoft. Il se construit et se déploie sans modification ; la campagne hebdomadaire le construit avec des valeurs d'essai.

## Variables

Le déploiement en un clic les demande avant la construction ; copiez `.env.example` pour un essai local.

- `BREVO_API_KEY` (requise) : La clé d'API Brevo qui envoie les courriels du formulaire. À obtenir ici : https://app.brevo.com/settings/keys/api
- `CONTACT_DESTINATAIRE` (requise) : L'adresse qui reçoit les messages du formulaire. À obtenir ici : https://help.brevo.com/hc/fr/articles/209467485
