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
- Fungal, Viral, or other infections

It is hoped that these Beacons will not only be able to help locate Beehives for marking
and observation purposes, but also to begin to log the health and activity of many 
wild and domestic Beehives. BY creating a larger data set of wild and domestic Beehives,
we can begin to track the overall health of our important crop pollinators, the Bees.

![Wild Beehive](https://patternagents.github.io/Beacons4Bees/hives/geo:45.4565208-122.7891868.png)

## How Does it Work? ##

Google EddyStone Beacons provide a URL (17 characters in length only!) to a smartphone when it
is in close proximity (around 30 meters) to the Beacon. By enabling the "Physical Web" in Google Chrome
and your Bluetooth Radio, you will be presented with a Notificiation and a Link to a Web Page when you
are close to a Beehive that has been tagged with a Beacon. By clicking on that (shortened) link,
you are directed to a page for that BeeHive. This could be any https:// (i.e. secure) URL.

That URL will need to be "shortened" using a shortening service like https://bit.ly or others.

You can also use Git.Io to shorten your URL :

```
$ curl -i https://git.io -F "url=https://github.com/..."
HTTP/1.1 201 Created
Location: https://git.io/abc123

$ curl -i https://git.io/abc123
HTTP/1.1 302 Found
Location: https://github.com/...
```

The index file may contain a snapshot of live data, including a link to the data repository (data history).
We may also include a forum link, where visitors to that Hive can log their visit and observations.

For this demonstration, we have organized some example pages by [Geo URI](https://en.wikipedia.org/wiki/Geo_URI_scheme).
For example, a directory (and web page) could be created for each hive/location using a form similar to :

  https://patternagents.github.io/Beacons4Bees/hives/geo:45.4565208-122.7891868.html

where "45.4565208-122.7891868" is the lattitude and longitude of the hive location.

## Are there already BeeHive Databases? Where? ##
There are several, often organized by country or region.
One effort that is already underway is the [Smart Citizen Project](https://smartcitizen.me/) 
for collecting (big) data worldwide, and several BeeHive makers and manufacturers are employing that (Wi-Fi) platform.
It uses a REST based web interface, combined with a sensor platform based on the Arduino development environment.
BeeHives and kits available from makers like [Open Source Beehives](http://opensourcebeehives.net/) 
and [Bee Thinking](http://www.beethinking.com/) here in Portland, can be instrumented with Wi-Fi Platforms like
the [Smart Citizen Project](https://smartcitizen.me/) for monitoring and collecting data.
While this is an excellent solution for backyard and commercial beehives, Wi-Fi platforms 
generally work best tethered to a power source like USB, or a wall adapter. 

Beacons for BeeHives augments that effort with a lower power solution for wild beehives, and more remote
applications in rugged terrain or third-world countries, based on Google EddyStone Beacons doing data logging,
and piggyback transfer of data using the smartphone cell service or Wi-Fi (or delayed upload once service becomes available.)

## Where can I get a Beacon? ##
We are working on a list of (open source) Beacon suppliers and materials, check back soon...

## How Can I Help? ##
We're starting a crowd sourcing campaign to get PatternAgents Beacon Kits out to folks who may be interested.
Please join our mailing list at [Patternagents](https://patternagents.github.io)


## I can't afford a Beacon, can you send me one? ##
We're putting together support/contribute links for these the pages, 
and if we get enough interest and support,
then we can begin to make hardware available for others to install.

[![](https://github.com/PatternAgents/Beacons4Bees/blob/master/images/beacons_for_bees.jpg "Beacons for Bees")](https://www.meetup.com/Digital-Design-Workshop/events/233724699/)

## ##


