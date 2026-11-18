# Nouveautés WallDock Pro / Release highlights

Ce dépôt public héberge les APK de WallDock Pro. Le code source de la version Pro est conservé dans un dépôt distinct.

This public repository hosts WallDock Pro APKs. The Pro source code lives in a separate repository.

## 0.18.4-pro — Gotham pendant toute la conversation / Full-conversation Gotham (18/11/2026)

- L'overlay **Gotham élégant** est désormais utilisé pendant l'écoute, la réflexion, la réponse vocale et les erreurs.
- Écoute : barres réactives au micro ; réflexion : balayage animé ; réponse : pulsations et panneau de texte ; erreur : signal lumineux discret.
- L'option Classique conserve l'apparence d'origine. Choix du thème dans WallDock Pro ou Home Assistant ESPHome.
- Aucun changement de la synthèse vocale ni du pipeline Assist.

*Gotham elegant now applies to the entire conversation: listening (micro-reactive bars), thinking (animated scan), speaking and errors. Classic remains available.*

## 0.18.3-pro — Gotham élégant / Gotham elegant (18/11/2026)

- Nouveau thème optionnel **Gotham élégant** : fond noir/anthracite, anneaux bleu acier plus fins, pulsations animées, réponse dans un panneau discret.
- Affichage Gotham seulement **pendant que l'assistant parle** ; l'écoute et la réflexion gardent le thème habituel.
- Choix **Classique** (par défaut) ou **Gotham élégant** dans WallDock Pro et dans Home Assistant via ESPHome.
- Le thème ne change ni la voix ni le pipeline de l'assistant.

*Optional Gotham elegant speaking-only overlay; Classic remains the default. Select the style in WallDock Pro or via Home Assistant ESPHome.*

## 0.18.2-pro — Synchronisation Home Assistant / HA sync (18/11/2026)

- Nouvelles entités de configuration ESPHome : **Nom affiché de l'assistant** et **Nom du mot personnalisé**.
- Modification et retour d'état depuis Home Assistant.
- Stabilisation des options des sélecteurs de mots de réveil pour limiter les états `unknown`.
- Après installation, recharger si besoin l'intégration ESPHome de WallDock.

*Assistant display name and custom wake word labels are exposed as Home Assistant settings; wake word select options use stable labels.*

## 0.18.1-pro — Alfred et noms personnalisés / Custom names (18/11/2026)

- Afficher « A.L.F.R.E.D. » ou un nom au choix dans l'animation vocale.
- Le nom visible est **indépendant** du mot de réveil. L'apprentissage d'un mot de réveil personnalisé reste local et expérimental.

*Customizable on-screen assistant name, independent from wake word recognition.*

## 0.18.0-pro — SmartFlow Daily

- Reconnaissance faciale locale et salutations personnalisées.
- Options de voix Android et voix unifiée expérimentale.
- SmartFlow Daily : météo, calendriers, maison, sécurité et trafic selon les entités HA disponibles.
- Fonctions Pro : interphone, kiosque, API REST, MQTT, contrôle à distance, onglets et lecteur PDF.

**Télécharger / Download** : [versions publiées / published releases](https://github.com/psycho1807/WallDock-Pro-Releases/releases). La présence d'une version dans cet historique ne garantit pas que son APK soit déjà publié.
