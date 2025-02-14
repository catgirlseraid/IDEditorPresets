validation tests

{
    "key": "aerialway:summer:access",
    "type": "combo",
    "label": "Access (summer)",
    "strings": {
        "options": {
            "entry": "Entry",
            "exit": "Exit",
            "both": "Both"
        }
    },
    "autoSuggestions": false,
    "customValues": false
}

<chunk id="aerialway:summer:access_type">
    <space/>
    <combo key="aerialway:summer:access" text="Access (summer)">
        <list_entry value="entry" display_value="Entry"/>
        <list_entry value="exit" display_value="Exit"/>
        <list_entry value="both" display_value="Both"/>
    </combo>
    <label text="Placeholder"/>
</chunk>


{
    "key": "aerialway:bubble",
    "type": "check",
    "label": "Bubble"
}


<chunk id="aerialway:bubble_boolean">
    <space/>
    <check key="aerialway:bubble" text="Bubble"/>
    <label text="Placeholder"/>
</chunk>

{
    "key": "aerialway:capacity",
    "type": "number",
    "minValue": 0,
    "label": "Capacity (per hour)",
    "placeholder": "500, 2500, 5000..."
}


<chunk id="aerialway_capacity_text">
    <space/>
    <text key="aerialway:capacity" text="Capacity (per hour)"/>
    <label text="Placeholder"/>
</chunk>


special format for colour because colour sucks

<chunk id="building_colour_text">
    <space/>
    <combo key="building:colour" text="Façade Color">
        <list_entry value="black" display_value="black"/>
        <list_entry value="white" display_value="white"/>
    </combo>
    <label text="Placeholder"/>
</chunk>

up to
Fields
addr=yes
aerialway=yes
area=yes
bath=yes
bridge=yes
building=yes
camera=yes
