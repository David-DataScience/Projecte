# Projecte
<h1 align="center">Projecte Final</h1>
La intenció d'aquest projecte es elaborar un model predictiu que ens pugui ajudar a pronosticar el nivell d'aigua de l'embassament de Darnius – Boadella. 
He escollit aquest embassament en concret entre tots els que formen part de les conques internes perque és l'unic on hi ha ubicada una estació meteorológica automàtica, 
de manera que podré veure si hi ha relació entre la precipitació recollida en aquesta estació i el nivell d'aigua de l'embassament, amb la intenció de millorar les predicciones 
que faci el model.<br><br>

Per a aquest afer  contem amb la base de dades  Quantitat d’aigua als embassaments de les Conques Internes de Catalunya proveïdes per l'Agència Catalana de l’Aigua (ACA) que he aconseguit al web del portal de dades obertes de la Generalitat de Catalunya: https://analisi.transparenciacatalunya.cat/Medi-Ambient/Quantitat-d-aigua-als-embassaments-de-les-Conques-/gn9e-3qhr
On es detalla l'estat dels embassaments de les Conques Internes de Catalunya a partir dels valors de Nivell de l’aigua a l’embassament, Volum embassat i Percentatge del volum embassat respecte la capacitat de l’embassament.<br><br>

Per un altre banda també contem amb les dades proveïdes per la Xarxa d’Equipaments Meteorològics de la Generalitat de Catalunya  (XEMEC). Concretament he demanat les dades de precipitació de  l'estació meteorológica automàtica situada a l'embassament de Darnius – Boadella, aconseguides a través del sistema de petició de dades del Servei Meteorologic de Catalunya (MeteoCat):
https://www.meteo.cat/wpweb/serveis/formularis/peticio-dinformes-i-dades-meteorologiques/peticio-dinformes-meteorologics/<br>

<h1 align="center">Contingut</h1>
El projecte està compost per 4 seccions:<br><br>
<ul>
  <li>
  <a href="https://github.com/David-DataScience/Projecte/blob/main/Preprocessament_1.ipynb" target="_blank">Preprocessament</a><br>
En aquest apartat hem manipulat les base de dades obtingudes per aquest projecte per adecuar-les a les nostres necessitats, per acabar creant una de sola més adient als nostres interessos. Posteriorment hem fet una analisi de la nova base de dades creada de manera estadística i gràfica.
   </li>
  <li>
<a href="https://github.com/David-DataScience/Projecte/blob/main/Autoreg_models_2.ipynb" target="_blank">Models de regressió</a><br>
    En aquesta secció desenvolupem una serie de models de regressió per intentar predir l'evolució del nivell de l'aigua de l'embassament de Darnius - Boadella.
    </li>
  <li>
<a href="https://github.com/David-DataScience/Projecte/blob/main/ARIMA_3.ipynb" target="_blank">Model ARIMA</a><br>
    Aquí desenvolupem el model d'autoregressio de mitjanes movils ARIMA per intentar fer la mateixa predicció que a l'apartat anterior.
    </li>
  <li>
<a href="https://github.com/David-DataScience/Projecte/blob/main/Paper.pdf" target="_blank">Paper del projecte</a><br>
    En aquest document PDF es descriu tot el procés que hem seguit a l'hora d'elaborar el nostre projecte, així com les conclusions a les que hem arribat al finalitzar-lo.
    </li>
 </ul>

