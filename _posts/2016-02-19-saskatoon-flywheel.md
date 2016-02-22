
# Intro
OK!
Let's say you wanted to supply your city's electricity entirely with renewable energy sources.
Let us further suppose, that you don't want the lights to go out or dim, when the wind stops blowing, or if it's cloudy outside.
You're going to need some kind of storage device, to compensate for the variation in power supply.

This is actually a [very large problem](http://physics.ucsd.edu/do-the-math/2011/09/got-storage-how-hard-can-it-be/) no matter what type of storage you choose.
I like flywheels, since they're relatively simple to calculate, and could be built with a wide variety of trade-offs between cost of materials, size, and mass.
For my own city, [Saskatoon](https://en.wikipedia.org/wiki/Saskatoon), I worked out the math very roughly a couple of years ago.
This city of about 250k people, would need a flywheel about the size of an office building downtown, to cover its energy needs for a couple days.
That was just the size and mass of filling it with rocks / dirt to get the mass.
It would then need some very large, expensive bearings.
Since having a partial or full vacuum on that size would be crazy-expensive, you'd be losing a lot of energy per day.

I want to revisit this, to see how accurate I was, and to see if I can make a smaller flywheel, that maybe is less expensive overall.
Maybe by using a fast-spinning one made of less total materials.
(Although they'd be more expensive per unit.)

According to [this document](https://www.saskatoon.ca/sites/default/files/documents/corporate-performance/environmental-corporate-initiatives/city-ENVIRO-FINAL-JULY29-web.pdf), Saskatoon used about 1.01 * 10^11 Wh in 2013, just in electricity.
I can only get to about 1.42 * 10^9 Wh by multiplying my own household usage per month by twelve months and 260k people (2011's population, apparently).
Thus, I assume the vast majority is from offices and industrial use.
Either way, I have a nice, easy, accurate ballpark/range of electricity usage to use in my calculations.

# Solid Flywheel
The energy for a solid flywheel is `1/4 mv^2`, where m is the mass, and v is the velocity at its outer edge.
This is before losses from friction, etc.
Given our electricity usage of 1.01 * 10^11, and a velocity of 125 m/s (450 km/h), the mass would need to be...9.2 * 10^10 kg.
That works out to about 1.14 * 10^7 m^3.
If that was a solid cylinder of steel, it would be about 250 m tall, and 250 m wide.
Eyeballing off of Google's handy dandy map view, that looks like two-ish blocks wide in both directions, or the size of the mall downtown.

If we doubled the speed, we quarter the mass required, which would give us a cylinder only 150 m tall and wide, or about a solid city block.
There's no way a city could build anything remotely like this.
I'll skip the math, and say that this would use up all the steel we're currently using for all our cars, trucks, factories...you get the idea.

# Dirt-cheap?
So maybe try and use something cheaper, like dirt?
Steel is about 5 times as dense as compacted dirt, and also provides structural integrity.
So, if you wanted to cheap out on the steel, you'd have to make the thing at more than double the width and height, to make up for the mass difference.
Plus, all the strength would be in a relatively small amount of steel, since you're trying to make most of the mass dirt-cheap.
So, the speed you could reliably spin this thing at would be far less, increasing the size again.
I'm going to skip the math here, and say that it's on the order of 10s or 100s of city-blocks, in size, since you're probably not going to want to make it very tall.
So...*possibly* feasible for Saskatoon, with our wide-open plains.
Maybe.
Cities in more densely-packed countries wouldn't have the space for it.

# Oops. That was a full year.
So, I forgot to make this thing only large enough for a small time of energy storage.
Let's make the math easy, and say I want it to be 64 times smaller, or a 4 times smaller in every direction.
Then my solid-steel flywheel is only 40-ish m tall and wide, and still provides energy for 5.7 days.
That's a full business week, and the thing is actually starting to look feasible again...sort of.
I mean, that would probably still be more steel than like, every car in the city, but maybe not all the trucks, and definitely not all the semis, tractors, or buildings.
Still, we need that steel for all of those things, so we're probably going to want to build it out of something cheaper.

# Must Go Faster!
The nice thing about our energy equation is that the velocity gets squared.
So, if you have a strong, light material like carbon fiber or something, you can get a lot more energy, for a lot less mass.
Of course, the air-friction will increase with the square of the velocity too, so it's going to need to be in a partial vacuum.
Still, if the thing is that much smaller, it's probably going to be actually feasible.

Calculations to come...
