# 🏍️ Site MotoPro - Instructions Vidéo

## ✅ Vidéo d'arrière-plan ajoutée !

J'ai ajouté le code pour une vidéo en arrière-plan dans le header. La vidéo tournera en boucle automatiquement.

## 📹 Où trouver des vidéos de moto GRATUITES ?

### **Option 1 : Pexels (RECOMMANDÉ)**
- Site : https://www.pexels.com/fr-fr/videos/
- 100% gratuit, sans attribution obligatoire
- Recherche : "motorcycle" ou "motorbike"
- Télécharge en format MP4

**Vidéos suggérées :**
- https://www.pexels.com/video/motorcycle-riding-on-road-2694434/
- https://www.pexels.com/video/person-riding-motorcycle-2278095/
- https://www.pexels.com/video/motorcyclist-on-road-2491283/

### **Option 2 : Pixabay**
- Site : https://pixabay.com/fr/videos/
- Gratuit, utilisation commerciale OK
- Recherche : "moto" ou "motorcycle"

### **Option 3 : Coverr**
- Site : https://coverr.co/
- Vidéos courtes parfaites pour sites web
- Recherche : "motorcycle" ou "vehicle"

### **Option 4 : Videezy**
- Site : https://www.videezy.com/
- Gratuit (certaines nécessitent attribution)
- Grande sélection de motos

## 🛠️ Comment ajouter ta vidéo ?

### **Étape 1 : Télécharge ta vidéo**
1. Va sur Pexels ou un autre site
2. Cherche "motorcycle" ou "motorbike riding"
3. Télécharge en MP4 (format Full HD recommandé)

### **Étape 2 : Renomme et place la vidéo**
1. Renomme ton fichier en : `video-moto.mp4`
2. Place-le dans le MÊME dossier que index.html

### **Étape 3 : C'est tout !**
Ouvre `index.html` et ta vidéo apparaîtra en arrière-plan ! 🎉

## ⚙️ Optimisation de la vidéo (IMPORTANT)

Pour que le site charge rapidement :

### **1. Compresse ta vidéo**
- Site gratuit : https://www.freeconvert.com/video-compressor
- Taille recommandée : max 10 MB
- Résolution : 1920x1080 (Full HD)
- Durée : 10-20 secondes suffisent (elle tournera en boucle)

### **2. Convertis en WebM (optionnel mais recommandé)**
- Site : https://cloudconvert.com/mp4-to-webm
- Format WebM = meilleure compression
- Nomme-le : `video-moto.webm`
- Place-le aussi dans le dossier

## 📁 Structure finale de ton dossier

```
mon-site/
├── index.html
├── styles.css
├── script.js
├── video-moto.mp4     ← TA VIDÉO ICI
└── video-moto.webm    ← (optionnel)
```

## 🎨 Personnalisation

Si tu veux modifier l'effet de la vidéo, dans `styles.css`, cherche `.hero-video` et modifie :

```css
.hero-video {
    opacity: 0.7;  /* Change la transparence (0.5 à 1) */
    filter: brightness(0.8);  /* Assombrit la vidéo */
}
```

## ⚡ Conseils Pro

1. **Durée idéale** : 10-20 secondes (elle tourne en boucle)
2. **Taille** : Max 10 MB pour un chargement rapide
3. **Résolution** : 1920x1080 suffit largement
4. **Contenu** : Évite les vidéos trop rapides ou saccadées

## 🆘 Problèmes courants

**La vidéo ne s'affiche pas ?**
- Vérifie que le nom est exactement : `video-moto.mp4`
- Vérifie que la vidéo est dans le même dossier que index.html

**La vidéo est trop lourde ?**
- Compresse-la sur freeconvert.com
- Réduis la durée à 15 secondes maximum

**La vidéo ralentit le site ?**
- Compresse davantage
- Utilise le format WebM en plus du MP4

---

**Besoin d'aide ?** Demande-moi et je t'expliquerai ! 😊