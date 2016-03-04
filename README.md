# Leaflet.Terminator
>


## Description
Overlay day and night regions on a Leaflet Earth map.

This is a fork of the original [Leaflet.Terminator](https://github.com/joergdietrich/Leaflet.Terminator) by [Jörg Dietrich](https://github.com/joergdietrich)


## Installation
### bower
`bower install https://github.com/FCOO/Leaflet.Terminator.git --save`

## Demo
http://joergdietrich.github.io/Leaflet.Terminator/ 

## Usage
Leaflet.Terminator extends the Polygon class. Adding the terminator to a leaflet map is as easy as 

    L.terminator().addTo(map)

### options
In addition to all Polygon options, Leaflet.Terminator has a new option "resolution", which gives the step size at which the terminator points are computed. 
The step size is 1°/resolution, i.e. higher resolution values have smaller step sizes and more points in the polygon. 
The default value is 2.




## Copyright and License
This plugin is licensed under the [MIT license](https://github.com/FCOO/Leaflet.Terminator/LICENSE).

Copyright (c) 2015 [FCOO](https://github.com/FCOO)

## Contact information

Jesper Larsen jla@fcoo.dk


## Credits and acknowledgements
[Leaflet.Terminator](https://github.com/joergdietrich/Leaflet.Terminator) by [Jörg Dietrich](https://github.com/joergdietrich)

## Known bugs

## Troubleshooting

## Changelog



