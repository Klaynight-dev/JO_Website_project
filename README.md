# README - Site Internet des Jeux Olympiques Paris 2024

## Contexte du Projet
Le Comité d’organisation des Jeux Olympiques Paris 2024 a pour mission de planifier, organiser, financer et livrer les Jeux Olympiques et Paralympiques à Paris. Le site Internet officiel des JO Paris 2024 est conçu pour promouvoir le sport, en particulier auprès des jeunes, tout en rendant accessibles des informations clés sur les disciplines sportives, les épreuves, et les athlètes. Il s'adresse à un public national et international, avec une forte dimension interactive, mettant en avant des portraits d'athlètes, des tableaux de médailles, des récits historiques, et bien plus encore. Ce projet vise à attirer un large public tout en développant l'image de la France à l'international.

## Enjeux et Attentes
À moyen terme, le Comité Paris 2024 souhaite accroître la visibilité du site à l’échelle mondiale, promouvoir le sport auprès des jeunes, et renforcer l'image de la France. Les objectifs sont de générer un nombre élevé de vues, de faciliter l’accès au sport via des liens vers les fédérations sportives, et de promouvoir des valeurs telles que l’inclusivité et l’accessibilité, notamment pour les personnes en situation de handicap.

## Cibles
Le site cible principalement :
- Le grand public : familles, jeunes, amateurs de sport.
- Les communautés sportives et les fédérations françaises.
- Les médias nationaux et internationaux.
- Les internautes internationaux intéressés par les JO.
- Une attention particulière est portée sur l'accessibilité du site pour les personnes en situation de handicap.

## Fonctionnalités et Informations

Le site doit intégrer les fonctionnalités et informations suivantes :

### Page d’accueil
- **Présentation générale** des JO Paris 2024 avec des visuels captivants.
- **Accès aux disciplines sportives** : Liste de toutes les catégories sportives (14 sports).
- **Grands moments** des JO avec des vidéos, photos et histoires marquantes.
- **Tableau des médailles** : Classement par pays avec un tableau interactif.
- **Présentation des sites des épreuves** : Localisation géographique et illustrations.
- **Liste des partenaires officiels**.
- **Menu de navigation** permettant d’accéder aux autres pages du site.

### Pages des Sports
Pour chaque sport, une page détaillée comportant :
- Un **pictogramme/logo** du sport.
- **Historique** et origine du sport.
- **Date de première apparition** aux JO.
- **Règles et techniques de base**.
- **Programme des épreuves** à Paris 2024 (dates et horaires).
- **Athlètes célèbres** : Portraits de 8 athlètes avec leurs médailles et photos.
- **Redirection vers la page de l’athlète** pour plus d’informations.
- **Vidéos et photos** pour illustrer le sport.

### Pages des Épreuves
Des informations complètes pour chaque épreuve :
- **Présentation générale** de l’épreuve.
- **Déroulement précis** (dates, horaires des phases).
- **Résultats** : Mise en avant des podiums et records battus.
- **Photos et vidéos** des moments clés.

### Profils des Athlètes
Pages dédiées aux athlètes, comprenant :
- **Biographie** détaillée.
- Nombre de participations aux JO, palmarès.
- **Médailles** : Détails sur les disciplines et résultats.
- **Actualité de l’athlète** : Nouveaux records, performances récentes.
- **Réseaux sociaux** et visuels associés.

### Fonctionnalités Complémentaires
- **Replay des performances** des athlètes, avec vidéos des JO passés.
- **Chiffres clés** sur l’envergure des JO 2024.
- **Jeux Paralympiques** : Section dédiée.
- **Relais de la flamme olympique** : Parcours et histoire.
- **Équipe organisatrice des JO** : Présentation des membres du Comité.

## Contraintes Techniques
- **Charte graphique** : Le site doit être conforme à l’identité visuelle des Jeux Olympiques de Paris 2024, intégrant les éléments graphiques officiels tels que la mascotte "Phryge".
- **Optimisation pour les appareils mobiles** : Le site doit être responsive et s'adapter aux smartphones et tablettes.
- **Accessibilité** : Le site doit être accessible aux personnes en situation de handicap, avec des fonctionnalités comme des sous-titres, des descriptions audio, et un design inclusif.

## Technologies Utilisées
- **Frontend** : HTML5, CSS3, JS.
```html
<script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
<script> 
    $(function(){
      $("#footer").load("../contents/html/footer.html"); 
    });
</script> 
  
<script> 
    $(function(){
      $("#nav").load("../contents/html/header.html"); 
    });
</script>

<div id="nav"></div>
<div id="footer"></div>
```

## Conclusion
Ce projet de site internet a pour but de rendre les Jeux Olympiques Paris 2024 accessibles, interactifs et engageants pour un large public, tout en favorisant la promotion du sport et des valeurs olympiques à l’échelle mondiale.
