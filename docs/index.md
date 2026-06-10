<table>
<colgroup>
<col style="width: 21%" />
<col style="width: 78%" />
</colgroup>
<tbody>
<tr>
<td rowspan="2"><img src="images/image2.jpeg"
style="width:1.38681in;height:1.47153in"
alt="logo_IGN_pour_lettre" /></td>
<td style="text-align: center;font-size: 32px;"><strong>Plugin "Chemin le plus court" v1.3.0</strong></td>
</tr>
<tr>
<td style="font-size: 16px;text-align: center;">Développeur  : Gérôme PECHEUR (IGN)</td>
</tr>
</tbody>
</table>


## Sommaire


- [1. Résumé](#resume)
- [2. Prérequis](#prerequis)
- [3. Installation](#installation)
- [4. Présentation](#presentation)
- [5. Utilisation](#utilisation)

<div  style="background-color: #00ADC5; border: 1px solid black; padding: 5px; text-align: justify;margin-bottom:10px;">
  <h2 id="1-resume" style="color: white;margin:0;" >1. Résumé</h2>
</div>

- Le plugin Chemin le plus court sélectionne tous les tronçons contigus
  entre 2 tronçons sélectionnés.

- L’itinéraire suivi par cette sélection est le plus court chemin entre
  les 2 tronçons sélectionnés.

- Il fonctionne sur 2 objets linéaires de la même couche.

- Il fonctionne dans n’importe quel projet quelles que soient les
  données (vecteur ou flux wfs).

- Ce plugin est compatible QGIS3 et QGIS4

<div  style="background-color: #00ADC5; border: 1px solid black; padding: 5px; text-align: justify;margin-bottom:10px;">
  <h2 id="1-prerequis" style="color: white;margin:0;" >2. Prérequis</h2>
</div>

- Version de QGIS : 3.28 ou supérieur (y compris QGIS4)

- Le plugin « maitre » doit préalablement être installé : 
[maitre-qgis-plugin sur GitHub](https://github.com/IGNF/maitre-qgis-plugin)

<div  style="background-color: #00ADC5; border: 1px solid black; padding: 5px; text-align: justify;margin-bottom:10px;">
  <h2 id="installation" style="color: white;margin:0;" >3. Installation</h2>
</div>

2 possibilités :

- Ouvrir QGIS, Allez dans Extensions/Installer/Gérer les extensions,
  cliquez sur Installer depuis un ZIP, sélectionner le fichier ZIP puis
  cliquez sur Installer le plugin.

<img src="images/image3.png" style="width:5.21279in;height:1.1624in" />

- Installation via l’installateur (\*\_PluginIGN_Installer)

Une fois installé le plugin doit être activé dans le menu Extensions/Gérer les extensions.
Ensuite il faut executer le plugin maitre afin d'integrer ce plugin dans le menu IGN et / ou dans une barre d'outils.


<div  style="background-color: #00ADC5; border: 1px solid black; padding: 5px; text-align: justify;margin-bottom:10px;">
  <h2 id="presentation" style="color: white;margin:0;" >4. Présentation</h2>
</div>

Exemple de barre d'outils configurée avec le plugin maitre :
<img src="images/image4.png" style="width:2.95833in;height:0.41667in" />

Le plugin Chemin le plus court est représenté par l’icône suivante : <img src="images/image8.png"/>

<div  style="background-color: #00ADC5; border: 1px solid black; padding: 5px; text-align: justify;margin-bottom:10px;">
  <h2 id="utilisation" style="color: white;margin:0;" >5. Utilisation</h2>
</div>

Sélectionner 2 tronçons de la même couche.

 Les deux tronçons doivent être visibles à l’écran.

 Cliquer sur l’icône de la barre d’outils ou dans le menu IGN.

 Les tronçons entre les 2 et formant l’itinéraire le plus court sont
 sélectionnés (ils s’ajoutent aux 2 déjà dans la sélection)

 <span class="mark">IMPORTANT</span> : le tronçon de départ et le
 tronçon d’arrivée doivent être visibles à l’écran.



 <img src="images/image6.png"
 style="width:2.47612in;height:1.43091in" />
 <img src="images/image7.png"
 style="width:2.67627in;height:1.41559in" />
