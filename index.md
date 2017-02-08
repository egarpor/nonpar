---
layout: default
title: First Nonparametric UC3M Workshop
---

<center>
<a href="http://www.uc3m.es/">
	<img style="width:100%;" id="UC3M" src="images/uc3m_stats.jpg">
</a>
</center>

## Scope

Conferences and discussions with some of the current leading experts in **Nonparametric Statistics**, held in the [Department of Statistics](http://portal.uc3m.es/portal/page/portal/dpto_estadistica/home) of [Carlos III University of Madrid](http://www.uc3m.es). 

<center>
<img style="width:100%;" id="March UC3M" src="images/march2.jpg">
<br>

<i>The Department of Statistics at UC3M (Getafe)</i>
</center>
<br>

## Speakers

| Speaker | Affiliation | Date | Topic |
|:-------:|:-----------:|:----:|:-----:|
| <img style="width:70px;" id="Davide La Vecchia" src="images/davide.png"><br>[Davide La Vecchia](http://unige.ch/gsem/rcs/members2/profs/d/) | Université of Genéve (Switzerland) | Friday 3rd | TBA |
| <img style="width:70px;" id="Thomas Verdebout" src="images/thomas.jpg"><br>[Thomas Verdebout](http://tverdebo.ulb.ac.be/) | Université libre de Bruxelles (Belgium) | Wednesday 8th | TBA |
<img style="width:70px;" id="Jacobo de Uña" src="images/jacobo.png"><br>[Jacobo de Uña](http://jacobo.webs.uvigo.es/) | Universidad de Vigo (Spain) | Friday 10th | TBA |
| <img style="width:70px;" id="Javier Cárcamo" src="images/javier.png"><br>[Javier Cárcamo](http://www.uam.es/personal_pdi/ciencias/jcarcamo/) | Universidad Autónoma de Madrid (Spain) | Wednesday 15th | TBA |
| <img style="width:70px;" id="Siegfried Hörmann" src="images/siegfried.png"><br>[Siegfried Hörmann](http://homepages.ulb.ac.be/~shormann/) | Université libre de Bruxelles (Belgium) | Friday 17th | TBA |
<img style="width:70px;" id="Eustasio del Barrio" src="images/tasio.jpg"><br>[Eustasio del Barrio](http://www.eio.uva.es/infor/personas/tasio.html) | Universidad de Valladolid (Spain) | Wednesday 22th | TBA |
<img style="width:70px;" id="Ricardo Fraiman" src="images/ricardo.jpeg"><br>[Ricardo Fraiman](http://www.cmat.edu.uy/cmat/docentes/rfraiman) | Universidad de la República (Argentina) | Friday 24th | TBA |

## Location

Seminars to be held in *Sala Costas Goutis* 10.0.23 (Getafe) at **13:00**. The is located at the ground floor of building 10 (*Campomanes*). The exact coordinates are given in the map below.

<style>
    #map {
        width: 100%;
        height: 400px;
    }
</style>

<script src="https://maps.googleapis.com/maps/api/js?key=AIzaSyAz_4NqV0U73b9QilPvJ8VshloQbIXzSTg&amp;sensor=false" type="text/javascript">
</script>
<script type="text/javascript">

    function init() {
        // Basic options for a simple Google Map
        // For more options see: https://developers.google.com/maps/documentation/javascript/reference#MapOptions
        var mapOptions = {

            // How zoomed in you want the map to start at (always required)
            zoom: 17,

            // The latitude and longitude to center the map (always required)
            center: new google.maps.LatLng(40.315099, -3.725728),

            // How you would like to style the map.
            // This is where you would paste any style found on Snazzy Maps.
            styles: [{"featureType":"landscape.man_made","elementType":"geometry","stylers":[{"color":"#f7f1df"}]},{"featureType":"landscape.natural","elementType":"geometry","stylers":[{"color":"#d0e3b4"}]},{"featureType":"landscape.natural.terrain","elementType":"geometry","stylers":[{"visibility":"off"}]},{"featureType":"poi","elementType":"labels","stylers":[{"visibility":"off"}]},{"featureType":"poi.business","elementType":"all","stylers":[{"visibility":"off"}]},{"featureType":"poi.medical","elementType":"geometry","stylers":[{"color":"#fbd3da"}]},{"featureType":"poi.park","elementType":"geometry","stylers":[{"color":"#bde6ab"}]},{"featureType":"road","elementType":"geometry.stroke","stylers":[{"visibility":"off"}]},{"featureType":"road","elementType":"labels","stylers":[{"visibility":"off"}]},{"featureType":"road.highway","elementType":"geometry.fill","stylers":[{"color":"#ffe15f"}]},{"featureType":"road.highway","elementType":"geometry.stroke","stylers":[{"color":"#efd151"}]},{"featureType":"road.arterial","elementType":"geometry.fill","stylers":[{"color":"#ffffff"}]},{"featureType":"road.local","elementType":"geometry.fill","stylers":[{"color":"black"}]},{"featureType":"transit.station.airport","elementType":"geometry.fill","stylers":[{"color":"#cfb2db"}]},{"featureType":"water","elementType":"geometry","stylers":[{"color":"#a2daf2"}]}]
        };

        // Get the HTML DOM element that will contain your map
        // We are using a div with id="map" seen below in the <body>
        var mapElement = document.getElementById('map');

        // Create the Google Map using out element and options defined above
        var map = new google.maps.Map(mapElement, mapOptions);

        // To add the marker to the map, use the 'map' property
        var markerUC3M = new google.maps.Marker({
            position: new google.maps.LatLng(40.314107, -3.726073),
            map: map,
            title:"Sala Costas Goutis 10.0.23"
        });

        //Content structure of info Window for the Markers
        var contentStringUC3M = $('<div class="marker-info-win">'+
        '<div class="marker-inner-win"><span class="info-content">'+
        '<strong>Sala Costas Goutis 10.0.23<\/strong>'+
        '<\/span>'+
        '<\/div><\/div>');

        //Create an infoWindow
        var infowindowUC3M = new google.maps.InfoWindow();

        //set the content of infoWindow
        infowindowUC3M.setContent(contentStringUC3M[0]);

        //open infowindow when the page loads
        infowindowUC3M.open(map, markerUC3M);

        //add click event listener to marker which will open infoWindow
        google.maps.event.addListener(markerUC3M, 'click', function() {
            infowindowUC3M.open(map,markerUC3M); // click on marker opens info window
        });

    }

    // When the window has finished loading create our google map below
    google.maps.event.addDomListener(window, 'load', init);

</script> 

<div id="map">
</div>
<br>

## Registration

No prior registration is required. Attendance is free of charge. 

## Organization

- Scientific comittee: Antonio Cuevas, Marc Hallin, and Daniel Peña.
- Organizing comittee: Eduardo García Portugués, Raúl Jiménez Recaredo (chair) and Susana Linares (secretary).

## Contact

In case of questions you may contact <edgarcia@est-econ.uc3m.es>.
