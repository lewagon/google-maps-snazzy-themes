# Embed a Google Map

```html
<div id="map" style="width: 100%; height: 400px;"></div>

<script type="text/javascript" src="https://maps.googleapis.com/maps/api/js"></script>

<script type="text/javascript">
  var myLatlng = new google.maps.LatLng(48.852937,2.364178);

  var myOptions = {
      zoom: 14,
      center: myLatlng,
      mapTypeId: google.maps.MapTypeId.ROADMAP,
      styles: []
  };

  var map = new google.maps.Map(document.getElementById('map'), myOptions);
  var marker = new google.maps.Marker({
      position: myLatlng,
      map: map,
      title:"You are here!"
  });
</script>
```

You can change the map style with [Snazzy Maps](http://snazzymaps.com/)
