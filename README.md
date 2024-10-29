# WebApplication2 / Tehtävä 5

A: Erittele keskeiset osat koodista, jotka toimivat yhdessä. Esimerkiksi ProductController.cs, products.json ja Product.cshtml

  - Views kansion sisältö (sivut)
  - HomeController
  - products.json
  - product.cs
  - site.js
  - site.css
  - Newtonsoft Nuget package

 
B: Selitä tiedostossa lyhyesti, miten nämä osat kommunikoivat keskenään ja miten tiedot haetaan ja näytetään.

Keskeinen sisältö, eli itse tuotteet löytyvät products.json tiedostosta. Tämän tiedoston sisältö serialisoidaan listaksi tuotteita (product.cs) HomeControllerin avulla. Tulokset näytetään näkymässä (product.cshtml), tulosten muotoiluun käytetään site.css tyylitiedoston sisältöä. Site.js tiedoston funktioita käytetään mm. esittämään valuutan symboli tuotetiedoissa.
