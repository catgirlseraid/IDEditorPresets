
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
{
"key": "barrier",
"type": "defaultCheck",
"label": "Barrier",
"geometry": [
"vertex"
],
"strings": {
"options": {
"undefined": "No",
"planter": "Yes"
}
}
}
{
"key": "books",
"type": "semiCombo",
"label": "Type of Books"
}
{
"key": "booth",
"type": "combo",
"label": "Booth",
"caseSensitive": true
}
{
"key": "boules",
"type": "typeCombo",
"label": "Type"
}
{
"key": "boundary",
"type": "combo",
"label": "Type"
}
{
"key": "brewery",
"type": "semiCombo",
"label": "Sold Beer brands",
"terms": [
"beer brand",
"beer dispensing",
"bottled beer",
"draft beer",
"on tap",
"tap beer"
]
{
"key": "bunker_type",
"type": "combo",
"label": "Type"
}
{
"key": "club",
"type": "typeCombo",
"label": "Type"
}
{
"key": "communication:",
"type": "multiCombo",
"label": "Communication Types"
}
{
"key": "construction",
"type": "combo",
"label": "Type"
}
{
"key": "consulting",
"type": "semiCombo",
"label": "Expertise"
}
{
"key": "country",
"type": "combo",
"label": "Country",
"snake_case": false,
"caseSensitive": true
}
{
"key": "currency:",
"type": "multiCombo",
"label": "Currency Types",
"terms": [
"bills",
"cash",
"coins",
"money"
],
"caseSensitive": true
}
{
"key": "cutting",
"type": "typeCombo",
"label": "Type",
"usage": "group",
"placeholder": "Default"
}
{
"key": "cycle_network",
"type": "networkCombo",
"label": "Network",
"snake_case": false,
"caseSensitive": true
}
{
"key": "cycleway",
"keys": [
"cycleway:left",
"cycleway:right"
],
"reference": {
"key": "cycleway"
},
"type": "directionalCombo",
"label": "Bike Lanes",
"placeholder": "Lane, Track, Contraflow, …",
"strings": {
"types": {
"cycleway:left": "Left Side",
"cycleway:right": "Right Side"
},
"options": {
"no": {
"title": "None",
"description": "No bike lane"
},
"lane": {
"title": "Standard Bike Lane",
"description": "A bike lane separated from auto traffic by a painted line"
},
"shared_lane": {
"title": "Shared Bike Lane",
"description": "A bike lane with no separation from auto traffic"
},
"track": {
"title": "Bike Track",
"description": "A bike lane separated from traffic by a physical barrier"
},
"share_busway": {
"title": "Bike Lane Shared With Bus",
"description": "A bike lane shared with a bus lane"
},
"separate": {
"title": "Cycleway Mapped Separately",
"description": "Indicates that cycleway was mapped as a separate geometry"
},
"opposite_lane": {
"title": "(Deprecated) Opposite Bike Lane",
"description": "Please update with oneway, oneway:bicycle, and cycleway:left/right=lane etc."
},
"opposite": {
"title": "(Deprecated) Contraflow Bike Lane",
"description": "Please update with oneway=yes, oneway:bicycle=no, and cycleway:both=no etc."
}
}
},
"autoSuggestions": true
}
{
"key": "date",
"type": "check",
"label": "Date"
}
{
"key": "denomination",
"type": "combo",
"label": "Denomination",
"prerequisiteTag": {
"key": "religion",
"valueNot": "none"
}
}
{
"key": "denotation",
"type": "combo",
"label": "Denotation"
}
{
"key": "depot",
"type": "combo",
"label": "Type"
}
{
"key": "design",
"type": "combo",
"usage": "manual",
"label": "Design"
}
{
"key": "destination",
"type": "semiCombo",
"label": "Destinations",
"snake_case": false,
"caseSensitive": true
}
{
"key": "design",
"type": "combo",
"label": "{design}",
"icons": {
"one-level": "roentgen-power_pole_1_level",
"two-level": "roentgen-power_pole_2_level",
"three-level": "roentgen-power_pole_3_level",
"four-level": "roentgen-power_pole_4_level",
"asymmetric": "roentgen-power_pole_asymmetric",
"triangle": "roentgen-power_pole_triangle",
"flag": "roentgen-power_pole_flag",
"delta": "roentgen-power_pole_delta",
"armless": "roentgen-power_pole_armless",
"armless_asymmetric": "roentgen-power_pole_asymmetric_armless",
"armless_triangle": "roentgen-power_pole_triangle_armless"
}
}

{
"key": "design",
"type": "combo",
"label": "{design}",
"icons": {
"one-level": "roentgen-power_tower_1_level",
"two-level": "roentgen-power_tower_2_level",
"three-level": "roentgen-power_tower_3_level",
"four-level": "roentgen-power_tower_4_level",
"asymmetric": "roentgen-power_tower_asymmetric",
"triangle": "roentgen-power_tower_triangle",
"flag": "roentgen-power_tower_flag",
"delta": "roentgen-power_tower_delta",
"delta_two-level": "roentgen-power_tower_delta_2_level",
"delta_tree-level": "roentgen-power_tower_delta_3_level",
"donau": "roentgen-power_tower_donau",
"barrel": "roentgen-power_tower_barrel",
"x-frame": "roentgen-power_tower_x_frame",
"y-frame": "roentgen-power_tower_y_frame",
"h-frame": "roentgen-power_tower_h_frame",
"h-frame_two-level": "roentgen-power_tower_h_frame_2_level",
"guyed_h-frame": "roentgen-power_tower_guyed_h_frame",
"portal": "roentgen-power_tower_portal",
"portal_two-level": "roentgen-power_tower_portal_2_level",
"portal_three-level": "roentgen-power_tower_portal_3_level"
}
}
{
"key": "door",
"type": "combo",
"label": "Door"
}
{
"key": "drink:",
"type": "multiCombo",
"label": "Drinks"
}
{
"key": "embankment",
"type": "typeCombo",
"label": "Type",
"usage": "group",
"placeholder": "Default"
}
{
"key": "emergency",
"type": "combo",
"label": "Type"
}
{
"key": "emergency_ward_entrance",
"type": "combo",
"label": "Type"
}
{
"key": "enforcement",
"type": "combo",
"label": "Type"
}
{
"key": "except",
"type": "combo",
"label": "Exceptions"
}
{
"key": "expected_rcn_route_relations",
"type": "number",
"label": "Adjacent Cycling Nodes"
}
{
"key": "expected_rwn_route_relations",
"type": "number",
"label": "Adjacent Walking Nodes"
}
{
"key": "fence_type",
"type": "combo",
"label": "Type"
}
{
"key": "fishing",
"type": "combo",
"label": "Fishing"
}
{
"key": "fitness_station",
"type": "typeCombo",
"label": "Equipment Type"
}
{
"key": "ford",
"type": "typeCombo",
"label": "Type",
"usage": "group",
"placeholder": "Default"
}
{
"key": "fortification_type",
"type": "combo",
"label": "Fortification Type",
"prerequisiteTag": {
"key": "archaeological_site",
"value": "fortification"
}
}
{
"key": "fountain",
"type": "combo",
"label": "Type"
}
{
"key": "frequency",
"type": "combo",
"label": "Operating Frequency"
}
{
"key": "frequency",
"type": "combo",
"label": "{frequency}",
"prerequisiteTag": {
"key": "electrified",
"valueNot": "no"
}
}
{
"key": "fuel",
"type": "combo",
"label": "Fuel"
}
{
"key": "gambling",
"type": "semiCombo",
"label": "Games"
}
{
"key": "gauge",
"type": "combo",
"label": "Gauge"
}
{
"type": "manyCombo",
"keys": [
"male",
"female",
"unisex"
],
"label": "Gender",
"placeholder": "Unknown",
"strings": {
"options": {
"male": "Male",
"female": "Female",
"unisex": "Unisex"
}
},
"terms": [
"access",
"female",
"male",
"unisex"
]
}
{
"key": "genus",
"type": "combo",
"label": "Genus",
"snake_case": false,
"caseSensitive": true,
"placeholder": "Acer, Platanus, Quercus …"
}
{
"key": "government",
"type": "typeCombo",
"label": "Type"
}
{
"key": "grades",
"type": "combo",
"label": "Grade Levels",
"terms": [
"educational stages"
],
"snake_case": false,
"caseSensitive": true
}
{
"key": "grape_variety",
"type": "semiCombo",
"label": "Grape Varieties"
}
{
"key": "guest_house",
"type": "combo",
"label": "Type"
}
{
"key": "hashtags",
"type": "semiCombo",
"label": "Hashtags",
"usage": "changeset",
"placeholder": "#example",
"caseSensitive": true
}
{
"key": "highway",
"type": "typeCombo",
"label": "Type"
}
{
"key": "highway",
"type": "typeCombo",
"label": "Type of Path",
"strings": {
"options": {
"path": "Cartpath",
"service": "Service Road"
}
},
"autoSuggestions": false
}
{
"key": "leisure",
"type": "defaultCheck",
"label": "Horseback Riding Center",
"strings": {
"options": {
"undefined": "No",
"horse_riding": "Yes"
}
},
"reference": {
"key": "leisure",
"value": "horse_riding"
}
}
{
"key": "house",
"type": "combo",
"label": "House Type"
}
{
"key": "incline",
"type": "combo",
"label": "Incline"
}
{
"key": "indoor",
"type": "typeCombo",
"label": "Type"
}
{
"key": "industrial",
"type": "combo",
"label": "Type"
}
{
"key": "information",
"type": "typeCombo",
"label": "Type"
}
{
"key": "lamp_mount",
"type": "combo",
"label": "Mount"
}
{
"key": "lamp_type",
"type": "combo",
"label": "Type"
}
{
"key": "landuse",
"type": "typeCombo",
"label": "Type"
}
{
"key": "language:",
"type": "multiCombo",
"label": "Languages"
}
{
"key": "leisure",
"type": "typeCombo",
"label": "Type"
}
{
"key": "liaison",
"type": "combo",
"label": "Type"
}
{
"key": "license_classes",
"type": "semiCombo",
"label": "Classes of Driver’s License"
}
{
"key": "line_attachment",
"type": "combo",
"label": "Line Attachment"
}
{
"key": "line_management",
"type": "combo",
"label": "Line Management",
"terms": [
"branching",
"line topology",
"termination"
]
}
{
"key": "location",
"type": "combo",
"label": "Location"
}
{
"key": "man_made",
"type": "typeCombo",
"label": "Type"
}
{
"key": "manhole",
"type": "typeCombo",
"label": "Type"
}
{
"key": "manufacturer",
"type": "combo",
"snake_case": false,
"caseSensitive": true,
"label": "Manufacturer"
}
{
"key": "map_size",
"type": "typeCombo",
"label": "Coverage"
}
{
"key": "maxaxleload",
"type": "combo",
"label": "Axle Weight Limit",
"snake_case": false,
"prerequisiteTag": {
"key": "bridge",
"valueNot": "no"
}
}
{
"key": "maxstay",
"type": "combo",
"label": "Time Limit",
"options": [
"15 minutes",
"30 minutes",
"45 minutes",
"1 hour",
"1.5 hours",
"2 hours",
"2.5 hours",
"3 hours",
"4 hours",
"1 day",
"2 days"
],
"autoSuggestions": false,
"snake_case": false
}
{
"key": "maxweight",
"type": "combo",
"label": "Weight Limit",
"snake_case": false
}
{
"key": "maxweight",
"type": "combo",
"label": "{maxweight}",
"snake_case": false,
"prerequisiteTag": {
"key": "bridge",
"valueNot": "no"
}
}
{
"key": "message",
"type": "combo",
"label": "Message"
}
{
"key": "mimics",
"type": "combo",
"label": "Mimics",
"terms": [
"camoflauged",
"disguised",
"looks like",
"tree"
]
}
{
"key": "model",
"type": "combo",
"label": "Model",
"caseSensitive": true
}
{
"key": "monitoring:",
"type": "multiCombo",
"label": "Monitoring"
}
{
"key": "museum",
"type": "combo",
"label": "Type"
}
{
"key": "natural",
"type": "typeCombo",
"label": "Natural"
}
{
"key": "opening_hours",
"type": "combo",
"label": "Hours",
"placeholder": "Unknown",
"snake_case": false,
"caseSensitive": true
}
{
"key": "parking",
"type": "combo",
"label": "Type",
"stringsCrossReference": "{parking}",
"options": [
"underground",
"multi-storey",
"surface"
],
"autoSuggestions": false,
"customValues": true
}
{
"key": "parking_space",
"type": "combo",
"label": "Type"
}
{
"key": "pipeline",
"type": "typeCombo",
"label": "Type"
}
{
"key": "place",
"type": "typeCombo",
"label": "Type"
}
{
"key": "plant",
"type": "combo",
"label": "Plant"
}
{
"key": "playground",
"type": "combo",
"label": "Type"
}
{
"key": "power",
"type": "typeCombo",
"label": "Type"
}
{
"key": "produce",
"type": "semiCombo",
"label": "Produce"
}
{
"key": "product",
"type": "semiCombo",
"label": "Products"
}
{
"key": "railway",
"type": "typeCombo",
"label": "Type"
}
{
"key": "rating",
"type": "combo",
"label": "Power Rating",
"snake_case": false,
"caseSensitive": true
}
{
"key": "type",
"type": "combo",
"label": "Type"
}
{
"key": "residential",
"type": "combo",
"label": "Type"
}
{
"key": "resort",
"type": "combo",
"label": "Type"
}
{
"key": "restriction",
"type": "combo",
"label": "Type"
}
{
"type": "restrictions",
"geometry": [
"vertex"
],
"usage": "manual",
"reference": {
"rtype": "restriction"
},
"label": "Turn Restrictions"
}
{
"key": "room",
"type": "combo",
"label": "Type"
}
{
"key": "route",
"type": "combo",
"label": "Type"
}
{
"key": "route_master",
"type": "combo",
"label": "Type"
}
{
"key": "ruins",
"type": "combo",
"label": "Type"
}
{
"key": "sample_collection",
"type": "semiCombo",
"reference": {
"key": "healthcare",
"value": "sample_collection"
},
"label": "Samples"
}
{
"key": "shelter_type",
"type": "combo",
"label": "Type",
"icons": {
"public_transport": "temaki-transit_shelter",
"picnic_shelter": "temaki-picnic_shelter",
"lean_to": "temaki-sleep_shelter",
"field_shelter": "temaki-horse_shelter"
}
}
{
"key": "shoes",
"type": "semiCombo",
"label": "Shoes"
}
{
"key": "shop",
"type": "typeCombo",
"label": "Type"
}
{
"key": "site",
"type": "combo",
"label": "Type"
}
{
"key": "species",
"type": "combo",
"label": "Species",
"snake_case": false,
"caseSensitive": true,
"placeholder": "Acer platanoides, Quercus robur, …"
}
{
"key": "stars",
"type": "combo",
"label": "Stars",
"terms": [
"rating"
]
}
{
"key": "stile",
"type": "combo",
"label": "Type"
}
{
"key": "street_cabinet",
"type": "combo",
"label": "Type"
}
{
"key": "studio",
"type": "combo",
"label": "Type"
}
{
"key": "support",
"type": "combo",
"label": "Support"
}
{
"key": "surveillance",
"type": "combo",
"label": "Surveillance Kind"
}