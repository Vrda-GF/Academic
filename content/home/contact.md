+++
# Contact widget.
widget = "contact"
active = true
date = 2016-04-20T00:00:00

title = "Contact"
subtitle = ""

# Order that this section will appear in.
weight = 70

# Automatically link email and phone?
autolink = false

# Email form provider
#   0: Disable email form
#   1: Netlify (requires that the site is hosted by Netlify)
#   2: formspree.io
email_form = 2

+++

<div id="map" style="width:100%;height:400px;background:yellow"></div>

<script>
function myMap() {
    var pos = {lat: 43.346580, lng: 17.796784}; 
    var map = new google.maps.Map(document.getElementById("map"), { 
      zoom: 15, 
      center: pos 
    }); 
    var marker = new google.maps.Marker({ 
      position: pos, 
      map: map,
      icon: 'http://www2008.gf.sve-mo.ba/osiguranje-kvalitete/images/OKGF_marker.png'
    }); 
}
</script>
<script src="https://maps.googleapis.com/maps/api/js?key=AIzaSyBtwl48LQbrdx0oB0tS1Yo8ZKqjMVW5c24&callback=myMap"></script>
