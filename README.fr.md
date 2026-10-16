<p align="center">
  <img src="assets/icon.png" width="96" height="96" alt="Icône de MioType">
</p>

<h1 align="center">MioType</h1>

<p align="center">
  <b>Parlez. Ça s’écrit.</b> Saisie vocale et traduction instantanée pour Mac.<br>
  Appuyez sur <kbd>Fn</kbd>, parlez, appuyez de nouveau sur <kbd>Fn</kbd> : le texte s’écrit à votre curseur, dans n’importe quelle app.
</p>

<p align="center">
  <a href="https://miotype.com/download"><b>Télécharger pour macOS</b></a> ·
  <a href="https://miotype.com">Site web</a> ·
  <a href="https://miotype.com/pricing">Tarifs</a>
</p>

<p align="center"><sub><a href="README.md">English</a> · <a href="README.zh-CN.md">简体中文</a> · <a href="README.de.md">Deutsch</a> · <a href="README.es.md">Español</a> · <a href="README.fr.md">Français</a> · <a href="README.it.md">Italiano</a> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.pt.md">Português</a> · <a href="README.ru.md">Русский</a></sub></p>

<p align="center">
  <a href="https://www.youtube.com/watch?v=lWkNX-c_a8k"><img src="assets/demo.jpg" width="720" alt="Vidéo de démonstration de MioType (1 minute)"></a><br>
  <sub><a href="https://www.youtube.com/watch?v=lWkNX-c_a8k">▶ Voir la démo d'une minute sur YouTube</a></sub>
</p>

---

Votre curseur peut être dans un terminal, VS Code, Cursor, le prompt de Claude Code ou de Codex, un fil Slack ou un message de commit : MioType écrit là où se trouve le focus.

## Raccourcis

| Touches | Effet |
|---|---|
| <kbd>Fn</kbd> | Appuyez pour commencer à parler, puis de nouveau pour écrire. <kbd>Esc</kbd> annule |
| <kbd>Fn</kbd> + <kbd>Space</kbd> | Posez n’importe quelle question. Sélectionnez d’abord du texte pour poser une question dessus, ou dites « raccourcis ça » pour le réécrire sur place |
| <kbd>Fn</kbd> + <kbd>Left Shift</kbd> | Parlez chinois, obtenez de l’anglais, et inversement |
| <kbd>Fn</kbd> + <kbd>Control</kbd> | Traduit la sélection. Un seul mot anglais ouvre une fiche de dictionnaire |
| <kbd>Fn</kbd> + <kbd>R</kbd> | Améliore la sélection sur place |
| <kbd>Fn</kbd> + <kbd>S</kbd> | Cherche un mot ou une expression |

Tous les raccourcis se modifient dans les Paramètres.

## Pourquoi les développeurs l’adoptent

- **Il écrit là où est votre curseur.** Pas de fenêtre à part, pas de copier-coller. Dictez un long prompt pour votre agent de code, la description d’une PR ou la réponse à une issue directement à sa place.
- **Le chinois mêlé d’anglais reste mêlé.** Dites « 把这个 function 改成 async » et c’est exactement ce qui s’écrit. Les termes anglais ne sont pas traduits en chinois.
- **Il apprend votre vocabulaire.** Corrigez un mot mal reconnu juste après la dictée (`kubectl`, `useEffect`, le nom d’un collègue) et MioType l’ajoute à votre dictionnaire pour la prochaine fois. Vous pouvez aussi importer un dictionnaire.
- **Le hors-ligne, à un interrupteur près.** Choisissez le modèle Whisper local dans les Paramètres : votre voix ne quitte jamais votre Mac. Ça marche sans réseau et sans compte.
- **Votre propre clé.** La reconnaissance et l’amélioration peuvent passer par votre propre fournisseur d’API plutôt que par MioType Cloud.

## Gratuit et payant

| | |
|---|---|
| **Local** | Gratuit pour toujours. Dictée hors ligne avec Whisper, traduction et amélioration avec votre propre clé d’API. Historique, dictionnaire et réglages restent sur votre Mac |
| **Cloud gratuit** | Connectez-vous pour obtenir 3 000 mots cloud par semaine |
| **MioType Cloud** | 100 000 mots cloud par mois pour la reconnaissance dans le cloud, l’amélioration et la traduction par IA, sans clé d’API. 9,99 $ US/mois, 59,99 $ US/an ou 149 $ US en une fois |

Détails sur la [page des tarifs](https://miotype.com/pricing). Tout achat est remboursable sous 14 jours, sans justification.

## Confidentialité

- Whisper local s’exécute entièrement sur votre Mac.
- En mode cloud, l’audio ou le texte de chaque requête passe par notre serveur vers Alibaba Cloud Model Studio, et le résultat vous revient directement. Notre serveur ne conserve ni audio ni texte : il n’enregistre que le nombre de mots, le type et l’heure de la requête, pour calculer votre quota.
- Avec votre propre clé, les requêtes partent directement de votre Mac vers le fournisseur choisi.
- Nous n’entraînons aucun modèle sur vos contenus et n’utilisons ni publicité ni traceurs.
- Politique complète (en anglais) : [miotype.com/privacy](https://miotype.com/privacy)

## Configuration requise

- Un Mac avec puce Apple (M1 ou plus récent)
- Autorisations Micro et Accessibilité. MioType vous les demande pendant la configuration

## Retours

Un bug ou une idée ? [Ouvrez une issue](https://github.com/miotype/miotype/issues/new/choose). Pour toute question privée, écrivez à [hi@miotype.com](mailto:hi@miotype.com).

Les notes de chaque version sont publiées dans [Releases](https://github.com/miotype/miotype/releases). Cliquez sur **Watch → Custom → Releases** pour être prévenu.

---

MioType n’est pas open source. Ce dépôt sert de suivi public des issues et de notes de version.
