## Beacons4Bees ##

Applying Google EddyStone Beacons to Geo-locating  Wild and Domestic Beehives

Google Eddystone Beacons provide a simple way to "tag" a physical location,
similar to the AltBeacon and iBeacon technologies. To date, Beacons have
been largley used for merchandising and marketing applications in malls and stores.
However, it also has more general application for locating objects in physical space,
such as finding your lost car keys, or indicating your proximity to wild or domestic Beehives.

There are many reasons to geo-tag wild and domestic Beehives, 
one is simply to raise awareness of HoneyBee Colony Collapse Disorder (CCD),
and the state of health of local Beehives; another would be to alert 
those that might be susceptible to anaphylactic shock that they should be 
mindful of their surroundings. (i.e. Don't climb that lovely tree with the huge wild Beehive in it...)

The electronics required for creating a Beacon have become inexpensive, with low power requirements,
thanks to commodity applications like Headphones, Headsets, Wireless Speakers, and Mice,
which have driven down the cost of materials with these large volume applications,
as well as improving the battery life of many devices.

These same electronics, namely pre-FCC certified Bluetooth Boards and Modules, 
are typically capable of several additional functions, such as reading sensors 
and logging the data from those sensor readings. Those locations with internet access 
can directly upload that sensor data to a repository in the cloud for later analysis.
Those locations without internet access, will need the help a beekeeper to pair their smartphone
to the Beacon and upload the logged data sets. It is also possible to provide volunteers with
a Smartphone Application that would allow them to use their data connection to "forward" sensor
data from the Beacons to the internet, when they are in Proximity to a Beacon. 
However, we are going to start simply, by tagging several wild, local hives 
and beginning to monitor their health using Beacons.

There are many causes that have been attributed to 
HoneyBee Colony Collapse Disorder (CCD),  including :
- Wild Habit Destruction
- Monocroping (single crops lack diverse food supplies)
- Neonicotinoids and general pesticide overuse
- Mites and parasites
- Fungal and other Viral infections

It is hoped that these Beacons will not only be able to help locate Beehives for marking
and observation purposes, but also to begin to log the health and activity of many 
wild and domestic Beehives. BY creating a larger data set of wild and domestic Beehives,
we can begin to track the overall health of our important crop pollinators, the Bees.

## How Does it Work? ##

Google EddyStone Beacons provide a URL (17 characters in length only!) to a smartphone when it
is in close proximity (around 30 meters) to the Beacon. By enabling the "Physical Web" in Google Chrome
and your Bluetooth Radio, you will be presented with a Notificiation and a Link to a Web Page when you
are close to a Beehive that has been tagged with a Beacon. By clicking on that (shortened) link,
you are directed to a page for that BeeHive, organized by [Geo URI](https://en.wikipedia.org/wiki/Geo_URI_scheme).
For example, a directory (and web page) can be created for each hive/location using the form :

  https://patternagents.github.io/Beacons4Bees/hives/geo/37.786971/-122.399677/index.html

where "/37.786971/-122.399677" is the lattitude and longitude of the hive location.
The index file may contain a snapshot of live data, including a link to the data repository (data history).
We may also include a forum link, whre visitors to that Hive can log their visit and observations.

## How Can I Join? ##
Put up a Beacon on your (or a Wild) Beehive, then submit a pull request for this repository to add the web page
for your site. Submissions with any overt marketing and advertising, or offensive material will not be accepted.

## Where can I get a Beacon? ##
We are working on a list of Beacon suppliers and materials, check back soon...

## I can't afford a Beacon, can you send me one? ##
We're putting a support/contribute link on the pages, and if we get enough interest and support,
we'll begin to make hardware available for others to install.

