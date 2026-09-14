# Bonjour, je suis Aniss 👋

Étudiant ingénieur en 4ème année, spécialité **Intelligence Artificielle**. Je construis des systèmes de recherche documentaire, des agents IA et des applications full-stack.

🇬🇧 [English version](README.md)

---

## 🤖 IA & Machine Learning

### [Agentic Vectorial Graph RAG](https://github.com/anissfhd/agentic-vectorial-graph-rag)
Un assistant documentaire sur une thèse scientifique de 206 pages qui **décide lui-même** comment répondre : recherche vectorielle, graphe de connaissances, les deux, ou « Je ne sais pas ». 7 méthodes de chunking et 7 modèles d'embedding réellement comparés, un graphe Neo4j Aura de 66 nœuds et 171 relations, et un agent Q-Learning orchestré par LangGraph. Chaque chiffre du README remonte à un artefact versionné y compris celui qui dit que la fusion RRF a *dégradé* les résultats.

`Python` `LangGraph` `FAISS` `Neo4j` `Q-Learning` `FastAPI` `React`

### [Taxi Joliette Voice Agent](https://github.com/anissfhd/taxi-joliette-voice-agent)
Un agent téléphonique IA qui prend des réservations de taxi en français québécois. La conversation est la partie facile la difficile est de **ne jamais créer deux fois la même course**, résolue par la sérialisation par appel doublée d'une idempotence `request_id`, et par un `z.literal(true)` Zod qui rend structurellement impossible de réserver sans confirmation explicite du client.

`TypeScript` `Twilio ConversationRelay` `OpenAI` `n8n` `Zod` `Docker`

### [Deep Learning — MLP, CNN, Seq2Seq](https://github.com/anissfhd/Projet-Deep-Learning)
Trois architectures pour trois topologies de données, avec la convolution et le pooling **écrits à la main** puis vérifiés contre PyTorch (différence maximale : 0). Démontre expérimentalement pourquoi l'initialisation constante des poids échoue la symétrie des neurones et ce que le biais inductif apporte réellement.

`PyTorch` `LeNet-5` `GRU` `Beam Search` `MNIST`

### [Qualité de l'air — Détection d'anomalies](https://github.com/anissfhd/air-quality-anomaly-detection)
Un an de mesures horaires de capteurs, et deux détecteurs d'anomalies qui ne s'accordent que sur **42 %** des événements. Le désaccord est le résultat : le Z-score se déclenche sur un polluant extrême, l'Isolation Forest sur une combinaison inhabituelle.

`pandas` `scikit-learn` `Isolation Forest` `Régression Ridge` `Jupyter`

### [AR 3D Menu](https://github.com/anissfhd/ar-3d-menu)
Une carte de restaurant en réalité augmentée : les photos d'un plat deviennent un vrai modèle 3D par photogrammétrie, nettoyé de ses fragments parasites et remis à sa **taille réelle**, puis posé sur la table du client depuis un QR code — sans application, sur Android comme sur iPhone. 101 tests réussis.

`Python` `Flask` `Photogrammétrie` `model-viewer` `WebXR` `ARKit` `Blender`

### [Sales AI Platform — Spécification](https://github.com/anissfhd/sales-ai-platform-specs)
Un travail de conception plutôt que du code : environ 68 000 mots définissant une plateforme autonome de prospection B2B multi-pays un cycle de vie en 13 étapes, la conformité comme barrière stricte, et un benchmark fournisseur complet.

`System Design` `Spécification produit` `Architecture`

---

## 💻 Développement logiciel

### [Site d'un cabinet de psychologie](https://github.com/anissfhd/cabinet-psychologue-website)
Un site pensé pour des parents inquiets : une vidéo de fond pilotée par le scroll, **figée sur chaque chapitre puis relancée à la frame exacte où elle s'était arrêtée**, une page dédiée à la prise de rendez-vous, et un envoi de mail qui ne stocke volontairement aucune donnée de santé.

`Next.js` `TypeScript` `Tailwind CSS` `Framer Motion` `Lenis`

### [HD Radar — Trainer de jeu](https://github.com/anissfhd/hd-radar-trainer)
Un trainer pour un jeu de 2002 sans SDK ni code source : radar et ESP en surimpression, création et contrôle de jusqu'à 50 soldats, clonage de véhicules, et deux utilitaires qui donnent à l'hôte l'autorité sur l'IA ennemie en coopération LAN. Environ 35 000 lignes de C++, bâties sur des offsets et des signatures mesurés dans le processus en cours.

`C++17` `Reverse engineering` `DirectX 9` `Dear ImGui` `Win32`

### [CDHubs — E-commerce de produits digitaux](https://github.com/anissfhd/cdhubs-digital-products)
Une boutique de vente de produits numériques, en trois briques déployables : une API NestJS + Prisma sur 11 modèles, une console d'administration Next.js, et une vitrine statique bilingue français/arabe pensée pour l'hébergement mutualisé.

`NestJS` `Prisma` `PostgreSQL` `Next.js` `TypeScript`

### [Club Sport — Plateforme de gestion](https://github.com/anissfhd/club-sport-management)
Membres, événements, entraînements, paiements et notifications au même endroit. Les échéances de paiement sont modélisées comme des lignes plutôt que comme un drapeau, ce qui rend la question « qui doit encore quoi » répondable.

`Django REST Framework` `Next.js` `JWT` `Tailwind CSS` `MySQL`

### [Azelle — Application d'échange linguistique](https://github.com/anissfhd/azelle-android)
Application Android qui met en relation autour de l'échange linguistique. Un onboarding guidé en 10 étapes construit un profil linguistique, langue maternelle, langues apprises avec un niveau pour chacune avec une progression persistée côté serveur : fermer l'application en cours d'inscription reprend là où on s'était arrêté.

`Kotlin` `Jetpack Compose` `Material 3` `Supabase`

### [Chess Infinity](https://github.com/anissfhd/chess-infinity)
Application Flutter de gestion de tournois pour un club d'échecs. Prototype à un stade précoce, un écran de lancement animé sur une ossature six plateformes.

`Flutter` `Dart`

---

<sub>Chaque dépôt documente ce qui fonctionne, ce qui ne fonctionne pas, et ce qui manque encore.</sub>
