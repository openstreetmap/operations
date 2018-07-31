# Equinix Amsterdam

One of the OSMF primary sites is hosted by Equinix in their AM6 Amsterdam data centre. Internet is a 1 Gbps port with 1 Gbps commit from Cogent.

## Visiting

The [building](https://www.openstreetmap.org/way/460515888) is at Duivendrechtsekade 80a, 1096 AH Amsterdam, Netherlands. Government picture ID is required, you will have to give the company name, and access must be set up through the Equinix portal.

When first arriving, ask for an orientation from an engineer. They can show you how to get to the rack and where to unpack stuff.

### On-site resources
In addition to any equipment we have, there are carts with a monitor and keyboard, ladders, and footstools in each data centre hall, and ear plugs by the elevator. Carts are available from staff. Power and network cables can be purchased if we run out.

### Food and drinks
Water and some vending machines are in the entrance area. For long visits, food can be ordered from [Sandwich Express](https://www.sandwich-express.nl), who regularly deliver there. Let security tell them the address and give directions. For more varity, thuisbezorgd.nl delivers to the area, but most delivery services will get lost trying to find the gates.

### Leaving checklist

Before leaving, check that

1. all blanks are reinstalled;
2. all cables are tidy, neat, labeled, and properly plugged in;
3. the monitor is unplugged;
4. any new equipment or cables are labeled;
5. the front and back of the rack are closed and locked;
6. the isles are clear and any garbage has been thrown out.

## Shipments

Shipments must be arranged through the Equinix portal. The procedure is

1. Place the order, making sure that "OpenStreetMap Foundation" is the addressee. Shipments addressed to Equinix or security will be refused. Use a carrier with a tracking number. 

2. Create an "Inbound Shipment (Carrier)" in the Equinix portal with the stimated arrival, number of boxes, tracking number, carrier, and shipment.

3. If no one will be onsite within 3 days of delivery, have them deliver the package to the cage/suite.

If packaging the shipment yourself, try to minimize cardboard and other packaging, as these need to be removed in a staging area.

If smart hands are to be used, create a smart hands order and save it as a draft, then submit it when the order has arrived.

## Cable and label standards

Label each machine front and back where it won't block airflow. Use 50mm labels when possibles.

Use black for PDU A and white for PDU B. Label PDU end with machine name and machine end with PDU name and outlet number, e.g. `PDU-A 1`

Use blue for Cat6a for eth0 to switch 1 and black for eth1 to switch 2. Grey for OOB to switch 1 or switch 2. Label switch end with machine name and machine end with switch number and port, e.g. `SW1 1`.

For all other equipment, label both ends of every cable.

A new machine will require
- five identical flag labels with name
- five labels with switch and port numbers
- two identical flat labels with name, 50mm preferred
- two flag labels with PDU name and outlet numbers
