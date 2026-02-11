# Signature Email - Morgane TREHEL

Signature email professionnelle compatible Gmail, Outlook et autres clients email.

## 🔗 Aperçu en ligne

Visitez la page GitHub Pages pour voir le rendu de la signature :  
**[https://thomerdos.github.io/signature-mail-morgane/](https://thomerdos.github.io/signature-mail-morgane/)**

## 📋 Description

Cette signature email a été conçue pour reproduire exactement le design créé sur Canva, tout en étant compatible avec tous les clients email (Gmail, Outlook, Apple Mail, etc.).

### Caractéristiques techniques :
- ✅ Structure en **tableaux HTML** (compatible avec tous les clients email)
- ✅ **Styles inline uniquement** (pas de CSS externe)
- ✅ Liens cliquables (téléphone et LinkedIn)
- ✅ Design responsive
- ✅ Code propre et optimisé (89 lignes vs 771 lignes initiales)

### Design :
- **Fond vert** : #7f9972
- **Texte nom/titre** : #d7b097 (couleur beige/saumon)
- **Texte contact** : #424141 (gris foncé)
- **Photo de profil** : cercle de 120px avec bordure blanche de 3px
- **Icônes** : 14x14px
- **Padding général** : 20px
- **Border-radius** : 8px

## 🖼️ Personnalisation

### 1. Remplacer les URLs des images

Avant d'utiliser la signature, vous devez remplacer les placeholders suivants dans le fichier `index.html` :

| Placeholder | À remplacer par | Description |
|-------------|----------------|-------------|
| `URL_PHOTO_PROFIL` | URL de votre photo | Photo de profil (recommandé : 240x240px minimum) |
| `URL_ICONE_TELEPHONE` | URL de l'icône téléphone | Icône téléphone (14x14px) |
| `URL_ICONE_LINKEDIN` | URL de l'icône LinkedIn | Icône LinkedIn (14x14px) |
| `URL_ICONE_LOCALISATION` | URL de l'icône localisation | Icône localisation (14x14px) |

### 2. Hébergement des images

Pour héberger vos images, vous avez plusieurs options :

#### Option A : GitHub (recommandé)
1. Créez un dossier `images/` dans ce repository
2. Ajoutez vos images
3. Utilisez les URLs du type : `https://raw.githubusercontent.com/Thomerdos/signature-mail-morgane/main/images/nom-image.png`

#### Option B : Service d'hébergement d'images
- [Imgur](https://imgur.com/)
- [ImgBB](https://imgbb.com/)
- [Cloudinary](https://cloudinary.com/)

#### Option C : Google Drive
1. Uploadez l'image sur Google Drive
2. Rendez-la publique
3. Utilisez l'URL de partage direct

### 3. Suggestions d'icônes

Vous pouvez télécharger des icônes gratuites depuis :
- [Flaticon](https://www.flaticon.com/) (gratuit avec attribution)
- [Font Awesome](https://fontawesome.com/) (exportez en PNG)
- [Icons8](https://icons8.com/) (gratuit avec attribution)
- [Feather Icons](https://feathericons.com/)

**Couleur recommandée pour les icônes** : #424141 (gris foncé) pour correspondre au texte

## 📧 Installation dans Gmail

### Étape 1 : Copier le code HTML
1. Ouvrez le fichier `index.html` dans votre éditeur de texte
2. Remplacez les URLs des images (voir section Personnalisation ci-dessus)
3. Copiez **uniquement le contenu du tableau** (de `<table cellpadding="0"...` jusqu'à `</table>`, lignes 10-87)
   - ⚠️ Ne copiez PAS les balises `<html>`, `<head>`, `<body>`

### Étape 2 : Créer la signature dans Gmail
1. Ouvrez Gmail
2. Cliquez sur l'icône ⚙️ (Paramètres) en haut à droite
3. Sélectionnez **"Voir tous les paramètres"**
4. Allez dans l'onglet **"Général"**
5. Descendez jusqu'à la section **"Signature"**
6. Cliquez sur **"Créer"** pour créer une nouvelle signature
7. Donnez-lui un nom (ex: "Morgane TREHEL")

### Étape 3 : Insérer le HTML
1. Dans l'éditeur de signature, cliquez sur l'icône **"<>"** (Insérer du HTML) en bas de l'éditeur
2. Collez le code HTML de la signature (le tableau uniquement)
3. Cliquez sur **"OK"**
4. Descendez en bas de la page et cliquez sur **"Enregistrer les modifications"**

### Étape 4 : Tester
1. Composez un nouvel email
2. Vérifiez que la signature s'affiche correctement
3. Envoyez-vous un email de test pour valider le rendu

## 💡 Conseils

### Pour Gmail
- Assurez-vous que toutes les images sont hébergées en **HTTPS** (pas HTTP)
- Les images doivent être accessibles publiquement
- Testez toujours en vous envoyant un email avant d'utiliser la signature

### Pour Outlook
1. Ouvrez Outlook Web (outlook.com ou outlook.office.com)
2. Allez dans Paramètres > Afficher tous les paramètres Outlook
3. Courrier > Composer et répondre > Signature électronique
4. Collez le code HTML (tableau uniquement)

### Pour Apple Mail
1. Créez d'abord la signature dans Gmail
2. Envoyez-vous un email avec la signature
3. Copiez la signature depuis l'email reçu
4. Collez-la dans Préférences > Signatures dans Apple Mail

## 🛠️ Dépannage

### Les images ne s'affichent pas
- Vérifiez que les URLs sont correctes et en HTTPS
- Vérifiez que les images sont accessibles publiquement
- Essayez d'ouvrir les URLs dans votre navigateur

### La mise en page est cassée
- Vérifiez que vous avez copié uniquement le tableau (pas le body/html)
- Assurez-vous de ne pas avoir modifié les attributs `cellpadding`, `cellspacing` ou `border`

### Les liens ne fonctionnent pas
- Vérifiez que les attributs `href` sont corrects
- Pour le téléphone : `tel:+33632567144`
- Pour LinkedIn : `https://www.linkedin.com/in/morgane-trehel`

## 📝 Licence

Ce projet est libre d'utilisation.

---

**Créé pour Morgane TREHEL** - Consultante en communication & stratégie
