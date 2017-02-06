## Overview

A series of seminars from some of the current leading experts in **Nonparametric Statistics**, held in the [Department of Statistics](http://portal.uc3m.es/portal/page/portal/dpto_estadistica/home) of [Carlos III University of Madrid](http://www.uc3m.es).

<center>
<img style="width:70%;" id="March UC3M" src="https://raw.githubusercontent.com/egarpor/nonparamarch/master/images/march2.jpg?token=ABNl9quGFSC6xeZ2IWvx7i3ylQnjP08rks5YoevwwA%3D%3D">
<br>

<i>The Department of Statistics at UC3M (Getafe)</i>
</center>

## Speakers

| Speaker | Looks like? | Affiliation | Date | Topic |
|:-------:|:-----------:|:-----------:|:----:|:-----:|
| [Davide La Vecchia](http://unige.ch/gsem/rcs/members2/profs/d/) | <img style="width:70px;" id="Davide La Vecchia" src="https://raw.githubusercontent.com/egarpor/nonparamarch/master/images/davide.png?token=ABNl9s2JNrjiz1cT7sNKjYr9S2nvX1KHks5YodK0wA%3D%3D"> | Université of Genéve | Friday 3rd | TBA |
[Thomas Verdebout](http://tverdebo.ulb.ac.be/) | <img style="width:70px;" id="Thomas Verdebout" src="https://raw.githubusercontent.com/egarpor/nonparamarch/master/images/thomas.jpg?token=ABNl9okfqwO-7vv4oI_hIO8ZX5noF1woks5YodFRwA%3D%3D"> | Université libre de Bruxelles | Wednesday 8th | TBA |
[Jacobo de Uña](http://jacobo.webs.uvigo.es/) | <img style="width:70px;" id="Jacobo de Uña" src="https://raw.githubusercontent.com/egarpor/nonparamarch/master/images/jacobo.jpg?token=ABNl9iQ31oz4wZYdojbe2r2rnSdDQ-6Iks5YodDQwA%3D%3D"> | Universidad de Vigo | Friday 10th | TBA |
[Javier Cárcamo](http://www.uam.es/personal_pdi/ciencias/jcarcamo/) | <img style="width:70px;" id="Javier Cárcamo" src="https://raw.githubusercontent.com/egarpor/nonparamarch/master/images/javier.jpg?token=ABNl9ms7gDJBVWvzgPFQ2wpH10TuOIvYks5YodDywA%3D%3D"> | Universidad Autónoma de Madrid | Wednesday 15th | TBA |
[Siegfried Hörmann](http://homepages.ulb.ac.be/~shormann/) | <img style="width:70px;" id="Siegfried Hörmann" src="https://raw.githubusercontent.com/egarpor/nonparamarch/master/images/siegfried.png?token=ABNl9tqb4iYp14dUU3SCTTwhuw9rpdaIks5YodLEwA%3D%3D"> | Université libre de Bruxelles | Friday 17th | TBA |
[TBA](tba) | TBA | TBA | TBA | TBA |
[Ricardo Fraiman](http://www.cmat.edu.uy/cmat/docentes/rfraiman) | <img style="width:70px;" id="Ricardo Fraiman" src="https://raw.githubusercontent.com/egarpor/nonparamarch/master/images/ricardo.jpeg?token=ABNl9t3dabPN9_9ZZjmh9tIAliugHtDnks5YodE5wA%3D%3D"> | Universidad de la República | Friday 24th | TBA |

## Location

Seminars to be held in *Sala Costas Goutis* 10.0.23 (Getafe) at 13:00. 

<style>
    #map {
        width: 100%;
        height: 350px;
    }
</style>

<script src="https://maps.googleapis.com/maps/api/js?key=AIzaSyAWD32Ge3oaMcGn4HwR0eGkxi-CDaUR1vc&sensor=false" type="text/javascript">
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

## Scientific comittee

[Raúl Jiménez Recaredo](http://portal.uc3m.es/portal/page/portal/dpto_estadistica/personal/raul_jimenez), [Marc Hallin](http://ecares.ulb.ac.be/index.php?option=com_comprofiler&task=userProfile&user=114&Itemid=263) and [Antonio Cuevas](https://www.uam.es/personal_pdi/ciencias/acuevas/).

## Organizing comittee

[Raúl Jiménez Recaredo](http://portal.uc3m.es/portal/page/portal/dpto_estadistica/personal/raul_jimenez) and [Eduardo García Portugués](https://egarpor.github.io).

## Contact

In case of doubts you may contact <edgarcia@est-econ.uc3m.es>.
