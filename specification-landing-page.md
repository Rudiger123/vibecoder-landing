# Spécification Détaillée - Landing Page Freelance Vibecoder

## 1. PALETTE DE COULEURS (4 couleurs max)

| Couleur | Hex | Usage |
|---------|-----|-------|
| **Primary** | `#0F172A` (Slate 900) | Titres, header, footer, texte principal |
| **Secondary** | `#3B82F6` (Blue 500) | CTA, liens, accents, badges |
| **Background** | `#FFFFFF` (White) | Fond principal |
| **Surface** | `#F8FAFC` (Slate 50) | Sections alternées, cartes |
| **Text Muted** | `#64748B` (Slate 500) | Sous-titres, descriptions |

## 2. TYPOGRAPHIE

| Élément | Police | Poids | Taille |
|---------|--------|-------|--------|
| **Titres H1** | Inter | 800 (ExtraBold) | 48px desktop / 32px mobile |
| **Titres H2** | Inter | 700 (Bold) | 36px desktop / 28px mobile |
| **Titres H3** | Inter | 600 (SemiBold) | 24px desktop / 20px mobile |
| **Body** | Inter | 400 (Regular) | 16px / 18px pour lead |
| **Petit texte** | Inter | 500 (Medium) | 14px |

- Line-height: 1.2 pour titres, 1.6 pour body
- Letter-spacing: -0.02em pour titres

## 3. LAYOUT PAR SECTION

### HEADER (Fixed, height: 70px)
- Logo/Nom à gauche: "Vibecoder" ou initiales
- Navigation à droite: Services | Projets | Contact
- Background: white avec ombre subtile au scroll
- Mobile: hamburger menu

### HERO (min-height: 90vh, centré)
- Container max-width: 1200px
- Contenu centré verticalement et horizontalement
- H1: Titre principal (2 lignes max)
- Sous-titre: max-width 600px, centré
- CTA bouton: padding 16px 32px, border-radius 8px
- Badge sous CTA: 3 items avec checkmarks

### SERVICES (padding: 100px 0)
- Titre section centré
- Sous-titre centré
- 3 cartes en grid (3 colonnes desktop, 1 colonne mobile)
- Gap: 32px entre cartes
- Carte: padding 32px, border-radius 16px, ombre légère
- Chaque carte: titre pack, "Pour qui", liste features, délai, prix

### PROJETS (padding: 100px 0, bg: surface)
- Titre section centré
- 3 projets en grid (3 colonnes desktop, 1 colonne mobile)
- Chaque projet: image (16:9), titre, description, stack, note "démo"
- Image: border-radius 12px, object-fit cover

### FOOTER (padding: 60px 0, bg: primary)
- Texte blanc
- Email + liens sociaux centrés
- Copyright en bas

## 4. COMPORTEMENTS INTERACTIFS

### Hover Effects
- **Boutons**: scale(1.02), ombre plus prononcée, transition 200ms ease
- **Cartes**: translateY(-4px), ombre augmentée, transition 300ms ease
- **Liens nav**: couleur secondary au hover, underline animation

### Scroll Effects
- Header: ajoute ombre après 50px de scroll
- Smooth scroll sur ancres
- Sections fade-in au scroll (optional)

### Mobile
- Menu hamburger: slide-in from right
- Cartes: stack vertical
- Hero: texte plus petit, padding réduit

## 5. RESPONSIVE BREAKPOINTS

- **Desktop**: > 1024px (3 colonnes)
- **Tablet**: 768px - 1024px (2 colonnes projets, 1 colonne services)
- **Mobile**: < 768px (1 colonne tout, menu hamburger)

## 6. ASSETS NÉCESSAIRES

3 images de projets démo à générer:
1. Landing Page Coach Fitness (mockup écran)
2. Landing Page Formation Marketing (mockup écran)
3. Landing Page SaaS (mockup écran)
