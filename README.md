# Embed a Google Map

```html
<div id="map" style="width: 100%; height: 400px;"></div>

<script type="text/javascript" src="https://maps.googleapis.com/maps/api/js"></script>

<script type="text/javascript">
  var myOptions = {
      zoom: 14,
      center: new google.maps.LatLng(48.852937, 2.364178),
      mapTypeId: google.maps.MapTypeId.ROADMAP,
      styles: []
  };

  new google.maps.Map(document.getElementById('map'), myOptions);
</script>
```

You can change the map style with [Snazzy Maps](http://snazzymaps.com/)