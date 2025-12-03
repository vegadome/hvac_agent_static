🎨 ÉCLAIRAGE & AMBIANCE

HDRI Environment Map - CRITIQUE

Actuellement : fond noir avec nodes mais pas d'HDRI
Besoin : un HDRI industriel/studio pour des réflexions réalistes et une illumination globale
Impact BabylonJS : réflexions environnementales, IBL (Image-Based Lighting)


Éclairage volumétrique

Ajouter du "god rays" / volumetric lighting pour l'atmosphère aseptique
Particulièrement important pour la Zone_A_Aseptic_Filling


Éclairage d'accentuation

Spots sur équipements clés (bioréacteurs, zones critiques)
Éclairage de sécurité (vert/rouge pour zones)



🖼️ TEXTURES & MATÉRIAUX

Textures PBR complètes - CRITIQUE

Actuellement : 32 matériaux PBR mais 0 textures !
Besoin urgent : Base Color, Normal, Roughness, Metallic maps
Pour : sols industriels, murs carrelés, acier inoxydable, verre, panneaux de contrôle


Textures procédurales à bake

Saleté/usure légère pour réalisme
Logos/signalétique GMP sur équipements
Marquages au sol (zones, flèches)



🌟 EFFETS VISUELS

Émissive materials

Écrans de contrôle lumineux
LEDs d'état sur équipements
Éclairage de sécurité/signalétique


Transparence & Refraction

Vitres de salles blanches
Hublots de bioréacteurs
Panneaux de séparation


Glow/Bloom effects

Pour les écrans et voyants
Compatible avec BabylonJS Glow Layer



📐 DÉTAILS GÉOMÉTRIQUES

Props & Assets détaillés

Tuyauterie visible (raccords, vannes)
Instrumentation (capteurs, jauges)
Mobilier labo (paillasses, tabourets)
Personnel (optionnel, silhouettes)


Détails architecturaux

Grilles de ventilation
Câbles/conduits apparents
Joints de dilatation
Systèmes de sprinklers



🎥 CAMÉRA & COMPOSITION

Points de vue stratégiques

Caméras multiples pré-positionnées
Depth of Field pour focus
Animation de caméra (flythrough)


Composition visuelle

Points d'intérêt clairement visibles
Hiérarchie visuelle (zones importantes mises en valeur)



💡 POST-PROCESSING (BabylonJS)

Effets post-process à prévoir

Color grading (teinte bleutée/technique)
Ambient Occlusion
Screen Space Reflections
Chromatic Aberration (subtil)
Vignette



🏷️ ORGANISATION & OPTIMISATION

LODs (Level of Detail)

Versions simplifiées pour performance web
Important pour 132 objets


Baking des lumières

Lightmaps pour les zones statiques
Réduit la charge GPU dans BabylonJS


Naming & Hiérarchie

Collections logiques pour interaction web
Tags pour filtres (ex: "equipment", "structure")



🎯 PRIORITÉS IMMÉDIATES
Top 3 à faire maintenant :

HDRI industriel (impact visuel maximal)
Textures PBR pour matériaux clés (sols, murs, équipements)
Matériaux émissifs pour écrans/voyants