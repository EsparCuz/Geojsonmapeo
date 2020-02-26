var geojson = {
    type: 'FeatureCollection',
    features: [{
      type: 'Feature',
      geometry: {
        type: 'Point',
        coordinates: [-103.4105122, 25.542698]
      },
      properties: {
        iconUrl:'',
        title: 'CLUB',
        description: 'SANTOS LAGUNA.'
      }
    },
    {
      type: 'Feature',
      geometry: {
        type: 'Point',
        coordinates: [-103.3383962, 20.6720375]
      },
      properties: {
        title: 'CLUB',
        description: 'CHIVAS'
      }
    },
    {
      type: 'Feature',
      geometry: {
        type: 'Point',
        coordinates: [-99.1331785,19.4326296]
      },
      properties: {
        title: 'CLUB',
        description: 'AMERICA'
      }
    },
    {
      type: 'Feature',
      geometry: {
        type: 'Point',
        coordinates: [-99.6569007,19.292545]
      },
      properties: {
        title: 'CLUB',
        description: 'TOLUCA'
      }
    },
    {
      type: 'Feature',
      geometry: {
        type: 'Point',
        coordinates: [-100.3152586,25.6802019]
      },
      properties: {
        title: 'CLUB',
        description: 'MONTERREY'
      }
    },
    {
      type: 'Feature',
      geometry: {
        type: 'Point',
        coordinates: [-98,18.833333]
      },
      properties: {
        title: 'CLUB',
        description: 'PUEBLA'
      }
    },
    {
      type: 'Feature',
      geometry: {
        type: 'Point',
        coordinates: [-116.9646629,32.5010188]
      },
      properties: {
        title: 'CLUB',
        description: 'TIJUANA'
      }
    },
    {
      type: 'Feature',
      geometry: {
        type: 'Point',
        coordinates: [-96.666667,19.333333]
      },
      properties: {
        title: 'CLUB',
        description: 'VERACRUZ'
      }
    },
    {
      type: 'Feature',
      geometry: {
        type: 'Point',
        coordinates: [-92.5000001,16.5000001]
      },
      properties: {
        title: 'CLUB',
        description: 'CHIAPAS'
      }
    },
    {
      type: 'Feature',
      geometry: {
        type: 'Point',
        coordinates: [-101.6825081,21.1218598]
      },
      properties: {
        title: 'CLUB',
        description: 'LEON'
      }
    }
  ]
  };

  // add markers to map
geojson.features.forEach(function(marker) {

    // create a HTML element for each feature
    var el = document.createElement('div');
    el.className = 'marker';
  
    // make a marker for each feature and add to the map
    new mapboxgl.Marker(el)
  .setLngLat(marker.geometry.coordinates)
  .setPopup(new mapboxgl.Popup({ offset: 25 }) // add popups
    .setHTML('<h3>' + marker.properties.title + '</h3><p>' + marker.properties.description + '</p>'))
  .addTo(map);
  });

  