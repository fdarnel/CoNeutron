# Guide Stratégique : Maîtriser CoNeutron

**CoNeutron** est une variante inversée du jeu abstrait *Neutron* (proposée par Mark Owen et Julian Richardson). Contrairement au jeu original où vous devez rapatrier le Neutron dans votre camp, **votre objectif est ici de propulser le Neutron sur la rangée de départ de votre adversaire** (la ligne 5 pour les Bleus, la ligne 1 pour les Rouges).

---

## 1. Les 3 Principes Fondamentaux

### A. L'inversion mentale : Ouvrir au lieu de fermer
* **Erreur fréquente :** Créer un « mur » devant la ligne adverse. Si vous bloquez l'accès à la ligne cible, vous empêchez le Neutron d'y glisser.
* **Bonne pratique :** Gardez des **couloirs ouverts** (colonnes ou diagonales dégagées) pointant directement vers la rangée de départ adverse.

### B. Le contrôle du centre (case C3)
* Au départ, le Neutron occupe **C3** (8 directions possibles).
* Dès que le Neutron quitte le centre pour un bord (colonnes A ou E), il perd 3 directions de glissade. Contrôler les cases centrales (**B3, C3, D3, C2, C4**) permet d'orienter le Neutron vers les failles de la défense ennemie.

### C. L'asphyxie (VICTOIRE PAR BLOCAGE)
* Un joueur qui ne peut plus déplacer le Neutron au début de son tour, ou qui ne peut plus bouger aucun de ses pions après avoir déplacé le Neutron, **perd immédiatement**.
* En fin de partie, encercler le Neutron avec vos pions tout en gardant un pion libre pour votre second temps de jeu est souvent plus sûr qu'une attaque frontale.

---

## 2. Ouvertures Clés (1er Tour des Bleus)

Au tout premier tour de la partie, les Bleus (rangée 1 : A1–E1) ne déplacent **pas** le Neutron : ils jouent uniquement un pion.

| Ouverture | Coup initial | Objectif stratégique |
| :--- | :--- | :--- |
| **L'Ouverture Centrale** | **C1 → C2** (ou B1 → B3) | Prend immédiatement de l'espace devant le Neutron pour lui servir de « butoir » et empêcher les Rouges de le renvoyer facilement vers la ligne 1. |
| **L'Aile Diagonale** | **A1 → A4** (ou E1 → E4) | Projette un pion loin sur le flanc pour menacer les cases d'angle adverses (A5 / E5) et créer des angles de rebond diagonaux. |
| **Le Verrou Latéral** | **B1 → D3** (diagonale) | Occupe une case pivot centrale tout en libérant la colonne B pour le repli défensif. |

> **Conseil contre l'IA Difficile :** Évitez de jouer *A1 → A4* et *E1 → E4* simultanément trop tôt ; l'IA exploitera le vide laissé sur votre rangée arrière (ligne 1) pour y glisser le Neutron en deux temps.

---

## 3. Tactiques Avancées pour Battre l'IA Difficile

L'IA en mode **Difficile** calcule sur 3 demi-tours (algorithme Minimax Alpha-Bêta) et valorise la proximité du Neutron avec votre ligne de départ ainsi que les menaces immédiates. Voici comment la piéger :

### 1. La Double Menace (Fourchette de glissade)
Le coup gagnant le plus fréquent consiste à placer le Neutron sur une case qui possède **deux lignes de vue dégagées** vers la rangée adverse (par exemple une colonne verticale ET une diagonale). L'IA ne peut déplacer qu'un seul pion par tour : elle ne pourra bloquer qu'un seul des deux couloirs.

### 2. Le Pion « Butoir » (Bumper)
Puisque les pièces ne s'arrêtent que contre un obstacle, placez un de vos pions **juste derrière la case cible** (sur la rangée adverse, par exemple en B5 ou D5 pour les Bleus) :
1. Dégagez une case sur la ligne adverse (ex. : attirez un pion rouge hors de C5).
2. Glissez l'un de vos pions sur **C5**.
3. Lors d'un tour suivant, utilisez vos autres pions pour aligner le Neutron dans la colonne C ou en diagonale vers une case adjacente libre sur la ligne 5.

### 3. Le Piège de Tempo (Zugzwang)
L'IA Difficile cherche toujours à éloigner le Neutron de sa propre base. Utilisez cette prévisibilité :
* Laissez volontairement un couloir apparent vers une case latérale (ex. A2 ou E2) où vous avez déjà préparé un pion d'interception.
* Lorsque l'IA y pousse le Neutron, elle réduit drastiquement la mobilité du Neutron et vous offre l'angle de rebond idéal vers sa ligne de fond.

### 4. Défense Élastique de votre Rangée
* Ne laissez jamais plus de **deux cases adjacentes vides** sur votre ligne de départ (ligne 1 pour Bleu, ligne 5 pour Rouge) tant que le Neutron a une diagonale libre vers votre camp.
* Gardez toujours au moins **un pion mobile** à l'arrière capable de coulisser horizontalement (ex. de A1 vers D1) pour couper une trajectoire.

---

## 4. Checklist Avant Chaque Coup

1. **Si je déplace le Neutron ici**, l'adversaire peut-il l'envoyer directement sur ma ligne de départ au coup suivant ?
2. **Quel pion vais-je jouer juste après le Neutron ?** (Ne déplacez jamais le Neutron sans avoir vérifié que votre second mouvement bloque la riposte adverse.)
3. **Ce mouvement ouvre-t-il une diagonale** vers la rangée ennemie ?
