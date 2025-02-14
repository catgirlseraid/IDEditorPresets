
{
"key": "building:material",
"type": "combo",
"label": "Material"
}
{
"key": "building:part",
"type": "combo",
"default": "yes",
"label": "Building Part"
}
{
"key": "camera:mount",
"type": "combo",
"label": "Camera Mount"
}
{
"key": "dance:style",
"type": "semiCombo",
"label": "Dance Styles"
}
{
"key": "destination:ref",
"type": "semiCombo",
"label": "Destination Road Numbers",
"snake_case": false,
"caseSensitive": true
}
{
"key": "destination:ref",
"type": "semiCombo",
"label": "{destination/ref}",
"prerequisiteTag": {
"key": "oneway",
"value": "yes"
},
{
"snake_case": false,
"caseSensitive": true
}
{
"key": "destination:symbol",
"type": "semiCombo",
"label": "Destination Symbols"
}
{
"key": "destination:symbol",
"type": "semiCombo",
"label": "{destination/symbol}",
"prerequisiteTag": {
"key": "oneway",
"value": "yes"
}
{
"key": "diplomatic:services:",
"type": "multiCombo",
"label": "Services"
}
{
"key": "disused:amenity",
"type": "typeCombo",
"label": "Type"
}
{
"key": "disused:railway",
"type": "typeCombo",
"label": "Type"
}
{
"key": "disused:shop",
"type": "typeCombo",
"label": "Type"
}
"key": "wheelchair",
"type": "radio",
"strings": {
"options": {
"yes": "Yes",
"limited": "Limited",
"no": "No"
}
},
"label": "Wheelchair Access",
"terms": [
"handicap access"
]
}
{
"key": "wholesale",
"type": "typeCombo",
"label": "Wholesale"
}
{
"key": "water",
"type": "combo",
"label": "Type"
}
{
"key": "waterway",
"type": "typeCombo",
"label": "Type"
}
{
"key": "wall",
"type": "combo",
"label": "Type"
}
{
"key": "voltage",
"type": "combo",
"label": "Voltage"
}
{
"key": "via",
"type": "semiCombo",
"label": "Via",
"snake_case": false,
"caseSensitive": true
}
{
"keys": [
"bus",
"trolleybus",
"tram",
"train",
"subway",
"light_rail",
"monorail",
"ferry"
],
"type": "manyCombo",
"label": "Vehicles",
"strings": {
"options": {
"bus": "Bus",
"trolleybus": "Trolleybus",
"tram": "Tram",
"train": "Train",
"subway": "Subway",
"light_rail": "Light Rail",
"monorail": "Monorail",
"ferry": "Ferry"
}
},
"reference": {
"key": "public_transport"
},
"prerequisiteTag": {
"keyNot": "aerialway"
}
}
{
"key": "valve",
"type": "combo",
"label": "Type"
}
{
"key": "utility",
"type": "semiCombo",
"label": "Utilities"
}
{
"key": "two_sided",
"type": "defaultCheck",
"label": "Two-Sided",
"terms": [
"double-sided"
],
"geometry": [
"line"
],
"strings": {
"options": {
"undefined": "No",
"yes": "Yes"
}
}
}
{
"key": "turning_circle",
"type": "combo",
"label": "Shape"
}
{
"key": "tunnel",
"type": "typeCombo",
"label": "Type",
"usage": "group",
"placeholder": "Default"
}
{
"key": "trench",
"type": "combo",
"label": "Type"
}
{
"key": "trees",
"type": "semiCombo",
"label": "Trees"
}
{
"key": "traffic_signals",
"type": "combo",
"label": "Type",
"default": "signal"
}
{
"key": "traffic_sign",
"type": "typeCombo",
"label": "Traffic Sign",
"snake_case": false,
"caseSensitive": true
}
{
"key": "trade",
"type": "typeCombo",
"label": "Type"
}
{
"key": "tourism",
"type": "typeCombo",
"label": "Type"
}
{
"key": "to",
"type": "text",
"label": "To"
}
{
"key": "tee",
"type": "semiCombo",
"label": "Tee Color/Type",
"reference": {
"key": "golf",
"value": "tee"
}
}
{
"key": "taxon",
"type": "combo",
"label": "Taxon",
"snake_case": false,
"caseSensitive": true,
"placeholder": "Acer platanoides Columnare, Pyrus calleryana Chanticleer …"
}
{
"key": "target",
"type": "combo",
"label": "Target",
"snake_case": false,
"caseSensitive": true
}
