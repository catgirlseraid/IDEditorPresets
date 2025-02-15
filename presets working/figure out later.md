
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
{
"key": "flag:type",
"type": "combo",
"label": "Flag Type"
}
{
"key": "garden:type",
"type": "combo",
"label": "Garden Type"
}
{
"key": "generator:method",
"type": "combo",
"label": "{generator/method}",
"stringsCrossReference": "{generator/method}",
"options": [
"water-storage",
"water-pumped-storage",
"run-of-the-river"
],
"autoSuggestions": false,
"prerequisiteTag": {
"key": "generator:source",
"value": "hydro"
}
}
{
"key": "generator:type",
"type": "combo",
"label": "Type"
}
{
"key": "historic:civilization",
"type": "combo",
"label": "Historic Civilization"
}
{
"key": "network:type",
"type": "combo",
"label": "Network Type",
"prerequisiteTag": {
"key": "network"
}
}
{
"key": "opening_hours:drive_through",
"type": "combo",
"label": "Drive Through Hours",
"placeholder": "Same as regular business hours",
"prerequisiteTag": {
"key": "drive_through",
"value": "yes"
},
"snake_case": false,
"caseSensitive": true
}
{
"key": "operator:type",
"type": "combo",
"label": "Operator Type",
"prerequisiteTag": {
"key": "operator"
}
}
{
"key": "parking:both:orientation",
"keys": [
"parking:left:orientation",
"parking:right:orientation"
],
"reference": {
"key": "orientation"
},
"type": "directionalCombo",
"label": "Parking Orientation",
"strings": {
"types": {
"parking:left:orientation": "Left side",
"parking:right:orientation": "Right side"
},
"options": {
"parallel": "Parallel to the Street",
"diagonal": "Diagonal in Relation to the Street (~45°)",
"perpendicular": "Meets the Street at a Straight Angle (~90°)"
}
},
"autoSuggestions": false,
"customValues": false
}
{
"key": "parking:both",
"keys": [
"parking:left",
"parking:right"
],
"reference": {
"key": "parking"
},
"type": "directionalCombo",
"label": "Parking",
"strings": {
"types": {
"parking:left": "Left side",
"parking:right": "Right side"
},
"options": {
"lane": "Roadside Lane",
"street_side": "Street-Side",
"on_kerb": "On Kerb",
"half_on_kerb": "Half On Kerb",
"shoulder": "Shoulder",
"no": "No",
"separate": "Parking mapped separately",
"yes": "Yes (unspecified)"
}
},
"autoSuggestions": false,
"customValues": false
}
{
"key": "plant:method",
"type": "combo",
"label": "Generation Method",
"stringsCrossReference": "{generator/method}",
"autoSuggestions": false
}
{
"key": "plant:source",
"type": "combo",
"label": "Energy Source",
"stringsCrossReference": "{generator/source}"
}
{
"key": "playground:theme",
"type": "combo",
"label": "Theme"
}
{
"key": "public_bookcase:type",
"type": "combo",
"label": "Type"
}
{
"key": "seamark:beacon_isolated_danger:shape",
"type": "combo",
"label": "Shape"
}
{
"key": "seamark:beacon_lateral:shape",
"type": "combo",
"label": "Shape"
}
{
"key": "seamark:buoy_lateral:shape",
"type": "combo",
"label": "Shape"
}
{
"key": "seamark:mooring:category",
"type": "combo",
"label": "Category"
}
{
"key": "seamark:wreck:category",
"type": "combo",
"label": "Category"
}
{
"key": "seamark:type",
"type": "combo",
"label": "Seamark",
"terms": [
"marine"
]
}
{
"key": "service:bicycle:",
"type": "multiCombo",
"label": "Bicycle Services"
}
{
"key": "service:vehicle:",
"type": "multiCombo",
"label": "Services"
}
{
"key": "siren:purpose",
"type": "combo",
"label": "Purpose"
}
{
"key": "source:population",
"type": "combo",
"label": "Population Source",
"prerequisiteTag": {
"key": "population"
},
"snake_case": false,
"caseSensitive": true,
"terms": [
"census",
"population reference"
]
}
{
"key": "surveillance:zone",
"type": "combo",
"label": "Surveillance Zone"
}
{
"key": "telecom:medium",
"type": "combo",
"label": "Medium"
}
{
"key": "toilets:position",
"type": "semiCombo",
"label": "Positions"
}
{
"key": "tower:construction",
"type": "combo",
"label": "Construction",
"placeholder": "Guyed, Lattice, Concealed, ...",
"icons": {
"freestanding": "roentgen-tube",
"guyed_lattice": "roentgen-lattice_guyed",
"guyed_tube": "roentgen-tube_guyed",
"lattice": "roentgen-lattice"
}
}
{
"key": "tower:type",
"type": "combo",
"label": "Type"
}
{
"key": "townhall:type",
"type": "combo",
"label": "Type"
}
{
"key": "voltage:primary",
"type": "combo",
"label": "Primary Voltage"
}
{
"key": "voltage:secondary",
"type": "combo",
"label": "Secondary Voltage"
}
{
"key": "voltage:tertiary",
"type": "combo",
"label": "Tertiary Voltage"
}
{
"keys": [
"access",
"foot",
"motor_vehicle",
"bicycle",
"horse"
],
"reference": {
"key": "access"
},
"type": "access",
"label": "Allowed Access",
"placeholder": "Not Specified",
"strings": {
"types": {
"access": "All",
"foot": "Foot",
"motor_vehicle": "Motor Vehicles",
"bicycle": "Bicycles",
"horse": "Horses"
},
"options": {
"yes": {
"title": "Allowed",
"description": "Access allowed by law; a right of way"
},
"no": {
"title": "Prohibited",
"description": "Access not allowed to the general public"
},
"permissive": {
"title": "Permissive",
"description": "Access allowed until such time as the owner revokes the permission"
},
"private": {
"title": "Private",
"description": "Access allowed only with permission of the owner on an individual basis"
},
"designated": {
"title": "Designated",
"description": "Access allowed according to signs or specific local laws"
},
"destination": {
"title": "Destination",
"description": "Access allowed only to reach a destination"
},
"customers": {
"title": "Customers",
"description": "Restricted to customers at the destination"
},
"dismount": {
"title": "Dismount",
"description": "Access allowed but rider must dismount"
},
"permit": {
"title": "Permit",
"description": "Access allowed only with a valid permit or license"
},
"unknown": {
"title": "Unknown",
"description": "Access conditions are unknown or unclear"
}
}
}
}
{
"key": "access_aisle",
"type": "combo",
"label": "Type"
}
"keys": [
"hiking",
"bicycle",
"mtb",
"horse",
"ski"
],
"type": "manyCombo",
"label": "Activity",
"strings": {
"options": {
"hiking": "Hiking",
"bicycle": "Cycling",
"mtb": "Mountain Biking",
"horse": "Horseback Riding",
"ski": "Skiing"
}
}
}
{
"type": "address",
"key": "addr",
"keys": [
"addr:block_number",
"addr:city",
"addr:block_number",
"addr:conscriptionnumber",
"addr:county",
"addr:country",
"addr:county",
"addr:district",
"addr:floor",
"addr:hamlet",
"addr:housename",
"addr:housenumber",
"addr:neighbourhood",
"addr:place",
"addr:postcode",
"addr:province",
"addr:quarter",
"addr:state",
"addr:street",
"addr:subdistrict",
"addr:suburb",
"addr:town",
"addr:unit"
],
"label": "Address",
"strings": {
"placeholders": {
"block_number": "Block Number",
"block_number!jp": "Block No.",
"city": "City",
"city!cn": "City/Prefecture/League",
"city!jp": "City/Town/Village/Tokyo Special Ward",
"city!vn": "City/Town",
"conscriptionnumber": "123",
"country": "Country",
"county": "County",
"county!jp": "District",
"district": "District",
"district!cn": "District/County/Banner",
"district!vn": "Arrondissement/Town/District",
"floor": "Floor",
"hamlet": "Hamlet",
"housename": "Housename",
"housenumber": "123",
"housenumber!jp": "Building No./Lot No.",
"neighbourhood": "Neighbourhood",
"neighbourhood!jp": "Machi/Chōme/Aza/Koaza",
"place": "Place",
"postcode": "Postcode",
"province": "Province",
"province!cn": "Province/Municipality/AR/SAR",
"province!jp": "Prefecture",
"quarter": "Quarter",
"quarter!jp": "Ōaza",
"state": "State",
"street": "Street",
"subdistrict": "Subdistrict",
"subdistrict!vn": "Ward/Commune/Townlet",
"suburb": "Suburb",
"suburb!jp": "Ward (政令市)",
"town": "Town",
"unit": "Unit"
}
},
"terms": [
"location"
]
}
{
"key": "advertising",
"type": "typeCombo",
"label": "Type"
}
{
"key": "advertising",
"type": "typeCombo",
"label": "Type"
}
{
"key": "aeroway",
"type": "typeCombo",
"label": "Type"
}
{
"key": "agrarian",
"type": "semiCombo",
"label": "Products"
}
{
"key": "amenity",
"type": "typeCombo",
"label": "Type"
}
{
"key": "animal_boarding",
"type": "semiCombo",
"label": "For Animals"
}
{
"key": "animal_breeding",
"type": "semiCombo",
"label": "For Animals"
}
{
"key": "animal_shelter",
"type": "semiCombo",
"label": "For Animals"
}