# 💻 CodeStart

**CodeStart** est une application web interactive et moderne conçue pour faciliter l'apprentissage du code (HTML, CSS, et JavaScript) de manière simple, ludique et accessible à tous, même sans aucune expérience préalable !

Inspirée des meilleures méthodes de gamification (comme Duolingo ou Mimo), l'application propose une interface soignée en mode sombre (Dark Mode) pour un confort visuel optimal pendant les sessions d'apprentissage.

---

## 🚀 Fonctionnalités principales

- **Apprentissage progressif :** Des leçons découpées en étapes simples (Explications, Quiz interactifs, et ateliers pratiques).
- **Système de récompense (XP) :** Gagne des points d'expérience (XP) à chaque leçon terminée et valide ta progression.
- **Éditeur de code intégré ("Try It") :** Teste ton code HTML et JavaScript directement dans l'application avec un aperçu en temps réel grâce à une sandbox sécurisée.
- **Design moderne & responsive :** Une interface épurée avec des animations fluides, des badges personnalisés pour chaque langage et un menu de navigation intuitif.

---

## 🛠️ Architecture technique & Bonnes pratiques

Ce projet a été développé localement sur **Visual Studio Code** avec une attention particulière portée à la propreté du code et à la séparation des préoccupations :

1. **`index.html` (Structure) :** Gère uniquement le squelette fixe et l'affichage des différents écrans de l'interface (Accueil, Leçons, Profil).
2. **`style.css` (Design) :** Regroupe toute la charte graphique, les variables de thèmes, les boutons personnalisés et les effets visuels avancés (textes en dégradé, animations dynamiques).
3. **`leçon.json` (Données) :** Centralise tout le contenu des cours, les questions des quiz et les exercices pratiques sous forme de données structurées.
4. **`script.js` (Logique) :** Le moteur JavaScript charge dynamiquement le catalogue JSON via l'API `fetch()`, gère l'état de l'application (calcul des XP, avancement dans les étapes) et injecte le contenu de manière fluide.

---

## 📈 Prochaines étapes de développement

- [ ] **Persistance des données :** Intégration du `localStorage` pour sauvegarder le score d'XP et la progression de l'utilisateur même après la fermeture du navigateur.
- [ ] **Catalogue enrichi :** Ajout de nouvelles leçons avancées pour CSS (Flexbox, Grid) et JavaScript (Fonctions, Manipulations du DOM).
- [ ] **Mode Pro :** Finalisation de l'écran de paiement fictif pour simuler un abonnement Premium.

---

*Développé avec passion pour dompter les bases du développement web !* 🚀
