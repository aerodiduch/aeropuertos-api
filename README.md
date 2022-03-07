# aeropuertos-api
Una API que trabaja sobre los aerodromos y aeropuertos de Argentina


Estoy desarrollando una API con información de aeropuertos y aeródromos argetinos. Está basado en web scrapping y MongoDB para reflejar la API propiamente dicha.

https://metarsarg-testing.herokuapp.com

Actualmente posee dos endpoints. El primero /metar/?metar=CODIGO que permite obtener el metar de la última hora. Reemplezar CODIGO con el identificador LOCAL de los aeródromos.

El segundo endpoint es /fullreport/?localcode=CODIGO donde devuelve toda la información disponible sobre ese aeródromo en texto claro.

El servicio da NOTAMS, MADHEL y METAR/TAF. 

API en desarrollo.
