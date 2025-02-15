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






    <chunk id="orientation_type">
        <space/>
        <combo key="orientation" text="Orientation">
            <list_entry value="parallel"/>
            <list_entry value="diagonal"/>
            <list_entry value="perpendicular"/>
        </combo>
        <label text="Placeholder"/>
    </chunk>

up to

barrier_planter.json
basin.json
beauty.json
bench.json
bicycle_parking.json
bicycle_road.json
bike_ride.json
bin.json
blind.json
blood_components.json
board_type.json
bollard.json
books.json
booth.json
bottle.json
boules.json
boundary.json
branch_brand.json
brand.json
brewery.json
bridge.json
bridge_combo.json
building.json
building_area.json
building_area_yes.json
bunker_type.json
button_operated.json
cables.json
cai_scale-IT.json
camp_site.json
capacity.json
capacity_parking.json
capacity_volume.json
caravans.json
cash_in.json
castle_type.json
changing_table.json
charge_fee.json
charge_toll.json
check_date.json
circumference.json
clothes.json
club.json
collection_times.json
collector.json
colour.json
comment.json
communication_multi.json
community_centre.json
connectivity.json
construction.json
consulate.json
consulting.json
content.json
conveying.json
conveying_escalator.json
count.json
country.json
country_flag.json
couplings.json
covered.json
covered_no.json
craft.json
crop.json
crossing.json
crossing_raised.json
cuisine.json
currency_multi.json
cutting.json
cycle_barrier.json
cycle_network.json
cyclestreet-BE-NL.json
cycleway.json
date.json
deflection.json
delivery.json
denomination.json
denotation.json
departures_board.json
depot.json
depth.json
descent.json
description.json
design.json
design_power_pole.json
design_power_tower.json
destination.json
destination_oneway.json
destination_waterway.json
devices.json
diameter.json
diameter_crown.json
diet_multi.json
diplomatic.json
direction.json
direction_cardinal-US-CA-NZ.json
direction_clock.json
direction_point.json
direction_vertex.json
direction_vertex_dual.json
dispensing.json
display.json
distance.json
dock.json
dog.json
dog_yes.json
door.json
door_type.json
drink_multi.json
drinking_water.json
drinking_water_available.json
drive_through.json
duration.json
ele.json
ele_node.json
electrified.json
email.json
embankment.json
embassy.json
emergency.json
emergency_combo.json
emergency_ward_entrance.json
enforcement.json
entrance.json
except.json
expected_rcn_route_relations.json
expected_rwn_route_relations.json
expressway-US.json
faces.json
fax.json
fee.json
fence_type.json
fire_mains.json
fire_service_inlet.json
fire_sprinkler.json
fireplace.json
fishing.json
fitness_station.json
fixme.json
flashing_lights.json
floating.json
flood_prone.json
footrest.json
ford.json
fortification_type.json
fountain.json
frequency.json
frequency_electrified.json
from.json
fuel.json
gambling.json
gauge.json
gender.json
gender_simple.json
genus.json
government.json
grades.json
grape_variety.json
group_only.json
guest_house.json
handicap.json
handrail.json
handrest.json
hashtags.json
hazard_boundary.json
healthcare.json
healthcare_therapist.json
heating.json
height.json
height_building.json
highchair.json
highspeed.json
highway.json
highway_cartpath.json
historic.json
hoops.json
horse_riding.json
horse_scale.json
hot_water.json
house.json
iata.json
icao.json
image.json
incline.json
incline_steps.json
indoor.json
indoor_type.json
industrial.json
informal.json
information.json
inscription.json
intermittent.json
intermittent_yes.json
internet_access.json
interval.json
irrigation_pivot.json
junction_line.json
kerb.json
kitchen.json
kneipp_water_cure_multi.json
label.json
lamp_mount.json
lamp_type.json
landuse.json
lane_markings.json
lanes.json
language_multi.json
layer.json
layer_1.json
leaf_cycle.json
leaf_cycle_singular.json
leaf_type.json
leaf_type_singular.json
leisure.json
length.json
level.json
level_semi.json
liaison.json
license_classes.json
lifeguard.json
lifeguard_check.json
line_attachment.json
line_management.json
lit.json
loc_name.json
location.json
location_pool.json
lock.json
lockable.json
locked.json
man_made.json
manhole.json
manufacturer.json
map_size.json
map_type.json
mapillary.json
marker.json
material.json
mattress.json
max_age.json
maxaxleload_bridge.json
maxheight.json
maxlength.json
maxspeed.json
maxstay.json
maxweight.json
maxweight_bridge.json
maxwidth.json
memorial.json
message.json
microbrewery.json
military_service.json
mimics.json
min_age.json
min_height.json
minspeed.json
mobile.json
model.json
monitoring_multi.json
mooring.json
museum.json
name.json
nat_name.json
natural.json
network.json
network_bicycle.json
network_foot.json
network_horse.json
network_road.json
note.json
nudism.json
office.json
official_name.json
oneway.json
oneway_yes.json
openfire.json
opening.json
opening_date.json
opening_hours.json
operator.json
organic.json
outdoor_seating.json
overlap.json
panoramax.json
par.json
parcel_dropoff.json
parcel_pickup.json
park_ride.json
parking.json
parking_entrance.json
parking_space.json
payment_multi.json
payment_multi_fee.json
phases.json
phone.json
picnic_table.json
pipeline.json
place.json
plant.json
playground.json
plots.json
polling_station.json
population.json
portable.json
post.json
power.json
power_supply.json
preschool.json
produce.json
product.json
pump.json
railway.json
ramp.json
rating.json
rcn_ref.json
real_fire-GB-IE.json
recycling_accepts.json
recycling_type.json
ref.json
ref_aeroway_gate.json
ref_bridge_number.json
ref_disc_golf_hole.json
ref_golf_hole.json
ref_highway_junction.json
ref_platform.json
ref_rail.json
ref_road_number.json
ref_room_number.json
ref_route.json
ref_runway.json
ref_sector.json
ref_stop_position.json
ref_taxiway.json
reg_name.json
relation.json
religion.json
reservation.json
residential.json
resort.json
resource.json
restriction.json
restrictions.json
room.json
rooms.json
roundtrip.json
route.json
route_master.json
royal_cypher-GB.json
ruins.json
rwn_ref.json
sac_scale.json
salt.json
sample_collection.json
sanitary_dump_station.json
screen.json
scuba_diving.json
seasonal.json
seats.json
second_hand.json
segregated.json
self_service.json
service.json
service_rail.json
service_times.json
shelter.json
shelter_type.json
shoes.json
shop.json
short_name.json
shower.json
side.json
site.json
smoking.json
smoothness.json
sms.json
social_facility.json
social_facility_for.json
source.json
spacing.json
species.json
sport.json
stars.json
start_date.json
static_caravans.json
step_count.json
stile.json
stop.json
street_cabinet.json
stroller.json
structure.json
structure_power.json
structure_waterway.json
studio.json
subject.json
substance.json
substation.json
substation_pipeline.json
supervised.json
support.json
surface.json
surveillance.json
swimming_pool.json
switch.json

