# n8n — Fichiers de support pour la formation freeCodeCamp.org / Gavin Lon

Résumé
------
Dépôt contenant les fichiers de support et la documentation pour la formation vidéo "Learn n8n" présentée par Gavin Lon (freeCodeCamp.org). La vidéo montre comment installer et utiliser n8n, et propose 4 exemples de workflows pratiques (chat AI, notifications WhatsApp d'urgence, etc.).

Crédits
-------
- Auteur de la vidéo : Gavin Lon  
- Chaîne / cours : freeCodeCamp.org  
- Date vidéo : 12 nov. 2025
- La vidéo : https://www.youtube.com/watch?v=GIZzRGYpCbM

Liens utiles
------------
- Support Files sur GitHub (fourni dans la vidéo) : [Support Files sur GitHub](https://github.com/GavinLonDigital/n8...)
- OAuth2 Explainer Video mentionné : [OAuth2 & OpenID Connect Explained (référence dans la vidéo)](https://www.youtube.com/watch?v=... )
- Hébergement recommandé (Hostinger) : [Hostinger - getstartedn8n](https://hostinger.com/getstartedn8n) — code promo : `GETSTARTED`

Contenu de la vidéo (chapitres / timestamps)
-------------------------------------------
0:00:00 — Introduction  
0:10:35 — Internet Standards, REST et OAuth2  
0:14:49 — Installation n8n (Hostinger / self-host)  
0:18:36 — Ex. 1 : Première workflow (Chatbot AI)  
0:21:23 — Ajouter un node AIAgent  
0:25:00 — Ajouter OpenAI Chat Model au sous-node AIAgent  
0:26:49 — Ajouter les identifiants pour OpenAI  
0:33:40 — Ajouter un System Prompt à AIAgent  
0:41:00 — Ajouter Memory Sub Node (contexte)  
0:43:35 — Tester le ChatBot  
0:45:27 — Connexion Hostinger & n8n  
0:46:42 — Ex. 2 : Enregistrement App Panique WhatsApp  
0:47:10 — Créer une Google Spreadsheet  
0:49:47 — Ajouter OnSubmission Form Trigger Node  
0:58:03 — Ajouter Google Sheets Node  
0:58:49 — Configurer OAuth2 pour Google Sheets  
1:15:22 — Ex. 3 : Notifications Panique WhatsApp  
1:17:27 — Ajouter WhatsApp Trigger Node et config credentials  
1:29:27 — Configurer les autres nodes (notifications)  
1:45:32 — Test des notifications Panique  
1:47:43 — Ex. 4 : Validation CV / Planification d'entretien  
1:52:32 — Configurer Google Drive Node (credentials)  
2:01:33 — Configurer Loop Node  
2:16:59 — Configurer Human in the Loop Node  
2:31:03 — Configurer AIAgent pour planifier sur Google Calendar  
2:54:21 — Tester CV Approval / Interview Scheduler  
3:04:06 — Abstract Sub-Workflow (séparation des concerns)  
3:15:59 — Utiliser WhatsApp pour converser avec le ChatBot  
3:19:57 — Utiliser WebHook Trigger Node  
3:22:32 — Utiliser HttpRequest Node pour appeler des APIs externes  
3:24:24 — Intégrer du code JS via Code Node  
3:28:58 — Outro

Exemples de workflows présents / montrés
----------------------------------------
- Chatbot AI (AIAgent + OpenAI)  
- App d'inscription "Panique" via Google Forms + Google Sheets  
- Notifications d'urgence via WhatsApp  
- Validation de CV + planification d'entretien (Human-in-the-loop + Google Calendar / Drive)

Installation rapide (exemples concrets)
---------------------------------------
1) Cloner le dépôt :
```bash
git clone https://github.com/Adam-s-tech/n8n_FCC_Workflows_Support_Docs.git
cd n8n_FCC_Workflows_Support_Docs
```

2) Ajouter ce README (si vous l'éditez localement) puis pousser :
```bash
git add README.md
git commit -m "Add README with video contents and links"
git push origin main
```

Comment importer les workflows dans n8n (exemple)
-------------------------------------------------
1) Ouvrez votre instance n8n (self-host ou cloud).  
2) Dans l'interface, cliquez sur "Workflows" → "Import" → collez le JSON du workflow (ou uploadez le fichier).  
3) Configurez les credentials (OpenAI, Google, WhatsApp) depuis l'onglet Credentials.  
4) Testez chaque node étape par étape.

Contribuer
----------
- Ouvrez une issue si vous voyez un problème ou manque d'information.  
- Proposez une PR si vous ajoutez des workflows, fichiers de config ou instructions d'installation.

Licence
-------
Suggéré : MIT — adaptez selon vos besoins.

Contact / Aide
--------------
Pour aide rapide, créez une issue sur ce dépôt ou contactez le mainteneur.

----
Fichier généré automatiquement — modifiez-le si vous voulez plus de détails (ex. : liens complets vers les fichiers de support, JSON des workflows, exemples de credentials).````
