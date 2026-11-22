# Dahira Khidmatul Khayril Hallamina Ahmada

Site du dahira : `index.html` (GitHub Pages) + base de données Supabase.

- Hébergement : GitHub Pages (Settings > Pages > Deploy from a branch > main / root).
- Données : Supabase. `supabase/schema.sql` contient le schéma de base. Les évolutions suivantes
  (vérification des codes de commission, envoi des e-mails de confirmation via pg_net/Brevo)
  ont été appliquées directement sur le projet Supabase.
- Le mot de passe administrateur et la clé d'envoi d'e-mails ne sont pas dans ce dépôt :
  ils sont stockés côté base de données et se gèrent depuis l'espace administrateur.
