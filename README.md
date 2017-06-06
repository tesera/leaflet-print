# leaflet-print
Simple leaflet control that posts url representing the map state to an http print endpoint.

```
map.addControl(L.Control.print('http://myprintserver.com'));

map.on('print:sent', function () {
    
});

map.on('print:done', function () {
    
});

```
