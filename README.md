# CornixPOI
 Coordinates and Data on POI within Star Citizen compatible with CornixSC

Formatting:
```
"name": "Name of Body",
"alt": "Discovered Name/ID",
"sys": "Solar System",
"type": "Planet/Moon/Asteroid",
"par": "Orbits Body",
"chld": "Orbiting Body"
"hab": "Habitable?",
"aff": "Governing Party",
"radGame": Ingame radius (km),
"radLore": Inlore radius (km),
"karm": Ingame Karmin Line (km),
"grav": Body Gravity / Earth Gravity,
"atm": Body Pressure / Earth Pressure,

"gloX": Coordinate X,
"gloY": Coordinate Y,
"gloZ": Coordinate Z (0),
"rotV": Rotation (deg/sec),
"period": Day Length (hrs),

"POI": [
    {
        "name": "POI Name",
        "desc": "POI Description",
        "type": "Attraction/Outpost",
        "gloZ": Approximate Global Z,
        "lat": Surface Latitude,
        "lon": Surface Longitude
    }
],

"ROI": [
    {
        "name": "ROI Name",
        "desc": "ROI Description",
        "type": "Landform/Race",
        "gloZ": Approximate Global Z,
        "coords": {
            "1": {
                "lat": Surface Latitude,
                "lon": Surface Longitude,
                "desc": "type, title"
            },
            "2": {
                "lat": Surface Latitude,
                "lon": Surface Longitude'
                "desc": "type, title"
            }
        }
    }
],

"links": [
            {
                "name": "Link Title",
                "url": "Link URL"
            },
]
```