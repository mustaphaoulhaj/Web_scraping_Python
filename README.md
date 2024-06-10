# Scraping de Données d'Hôtels à partir de Booking.com

Ce projet a pour objectif de scraper les données des hôtels du site **Booking** pour la région Île-de-France et d'enregistrer les informations recueillies dans un fichier Excel.

## Prérequis

Avant de commencer, assurez-vous d'avoir installé les bibliothèques suivantes :

- Python 3.11.5
- `Requests`
- `Beautifulsoup4`
- `Pandas`


## Étapes du Projet

![Capture Page Web](https://github.com/mustaphaoulhaj/Web_scraping_Python/assets/127968969/8ee503d4-9706-4e14-9b02-761ae90fee50)

**1)- Téléchargement du contenu de la page :** : 
Nous commençons par télécharger le contenu HTML de la page en utilisant la bibliothèque **Requests**. Nous vérifions ensuite l'accessibilité de la page (code de réponse 200). Il est important de noter que certains sites web n'autorisent pas le scraping pour des raisons de conformité au RGPD.

**2)- Analyse du contenu HTML :**
Nous analysons le contenu HTML à l'aide de la bibliothèque **BeautifulSoup**.

**3)- Extraction des données :**
Nous extrayons les données des hôtels en ciblant les balises HTML spécifiques contenant les informations souhaitées. Pour identifier une balise spécifique, il suffit de sélectionner la donnée à extraire, de faire un clic droit, puis de cliquer sur "Inspecter" pour afficher la balise correspondante.

**4)- Enregistrement des Données :**
Nous sauvegardons les données extraites dans un fichier Excel 

## Résultats
Vous pouvez consulter le script Python ainsi que la base de données extraite au format Excel pour voir les résultats obtenus.


## Conclusion
Le web scraping est essentiel pour extraire, traiter et analyser des données à jour à partir de sites web. Pour ce projet, nous avons utilisé la bibliothèque **BeautifulSoup**, mais d'autres librairies comme **Selenium** peuvent aussi être utilisés. Cela montre l'importance de l'automatisation dans la collecte de données actuelles et la facilité avec laquelle nous pouvons les analyser pour prendre des décisions éclairées.
