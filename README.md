# Flyer Stand Afro Gourmets - Marché de Noël 2026 (Le Plessis-Trévise)

Flyer officiel d'une page A4 au format web (HTML5 / CSS3 purs) pour le stand **Afro Gourmets** lors du Marché de Noël 2026 du Plessis-Trévise (12 et 13 décembre 2026).

---

## 🎨 Caractéristiques & Style

- **Mise en page :** Format A4 Portrait exact (`@page { size: A4 portrait; margin: 0; }`), optimisé pour l'impression sans saut de page.
- **Design :**
  - **Fond :** Teinte crème délicate (`#fffdf5`) avec micro-motif festif.
  - **Palette des îles :** Vert profond (`#1b4332`), rouge piment (`#c0392b`), orange tropical (`#e67e22`) et jaune safran (`#f39c12`).
  - **Typographies :** Google Fonts *Playfair Display* (titres élégants), *Montserrat* (texte lisible) et *Caveat* (sous-titre manuscrit).
  - **Pastilles & Badges :** Pastilles rouges numérotées avec icônes SVG pour chaque section, filets décoratifs horizontaux, et pastilles dorées arrondies avec gradient métallisé pour l'affichage des prix.
  - **Décorations de Noël :** Décor de Noël fait main en SVG/CSS aux quatre coins (branches de sapin, feuilles de houx, boules dorées et rouges, étoiles scintillement).
- **Responsive :** Adapté à la fois pour un affichage sur écran et pour l'impression ou l'export PDF.

---

## 📁 Structure du projet

```
.
├── index.html          # Structure de la page HTML5 (sémantique)
├── style.css           # Styles CSS3, variables, responsive & règles @media print
├── images/             # Visuals des plats, desserts et boissons
│   ├── pate-antillais.jpg
│   ├── rougail-saucisse.jpg
│   ├── gaufre.jpg
│   ├── jus-bissap.jpg
│   ├── jus-gingembre.jpg
│   ├── planteur-citron.jpg
│   └── planteur-exotique.jpg
├── flyer.pdf           # Exemple d'export PDF A4 haute qualité généré
└── README.md           # Instructions d'utilisation et d'exportation
```

---

## 💻 Comment ouvrir la page dans un navigateur

1. Clonez ou téléchargez le dépôt sur votre ordinateur.
2. Ouvrez directement le fichier `index.html` avec n'importe quel navigateur moderne (Google Chrome, Mozilla Firefox, Microsoft Edge ou Apple Safari) :
   - **Double-cliquez** sur `index.html`, ou
   - Faites **Glisser-Déposer** de `index.html` dans votre navigateur, ou
   - En ligne de commande :
     ```bash
     # macOS
     open index.html

     # Linux
     xdg-open index.html

     # Windows
     start index.html
     ```

---

## 🖨️ Comment exporter en PDF (Impression fidèlement dimensionnée)

Le flyer utilise des règles `@media print` strictes calibrées pour le format A4. Pour obtenir un fichier PDF parfait :

### Depuis Google Chrome / Microsoft Edge / Brave :
1. Ouvrez `index.html` dans le navigateur.
2. Ouvrez le menu d'impression via **Ctrl + P** (Windows/Linux) ou **Cmd + P** (macOS).
3. Réglez la **Destination** sur **"Enregistrer au format PDF"** (Save as PDF).
4. **Format de papier :** Sélectionnez **A4**.
5. **Orientation :** Sélectionnez **Portrait**.
6. **Marges :** Choisissez **Aucune** (None).
7. **Options d'impression / Paramètres supplémentaires :**
   - ✅ Cochez la case **Graphiques d'arrière-plan** (Background graphics).
   - ❌ Décochez la case **En-têtes et pieds de page** (Headers and footers).
8. Cliquez sur **Enregistrer** et choisissez l'emplacement de sauvegarde.

### Depuis Mozilla Firefox :
1. Ouvrez `index.html` dans Firefox.
2. Appuyez sur **Ctrl + P** (Windows/Linux) ou **Cmd + P** (macOS).
3. Sélectionnez **Enregistrer au format PDF**.
4. **Format de papier :** A4.
5. **Marges :** Aucune.
6. Cochez **Imprimer les arrière-plans**.
7. Cliquez sur **Enregistrer**.

---

## 🍽️ Contenu du Stand

- **Entrées & Plats :** Pâté antillais (porc/poulet) - 2,50 € | Rougail Saucisse, haricots rouges & riz blanc - 9,90 €
- **Desserts :** Gaufre gourmande (sucre, chocolat, beurre de caramel, confiture) - 3,00 €
- **Boissons :** Jus de Bissap - 3,00 € | Jus de Gingembre - 3,00 € | Planteur exotique ou citron (verre 3,50 € / litre 26,00 €) | Eau minérale - 1,50 €
- **Logistique :** Prestataire Afro Gourmets (Nadia & Expédite), besoin technique : prise électrique à proximité (maintien au chaud).
