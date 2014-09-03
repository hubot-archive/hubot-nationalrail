# Hubot National Rail

I wrote hubot-national-rail in response to nationalrail.coffee by @JaimeMagee.
I wanted to be able to fuzzy-search by station, not by official station codes I
could never remember.

## Configuration

You need to set the following:

 - `HUBOT_DEFAULT_STATION` set this to station code of your nearest station ([see here for codes](https://en.wikipedia.org/wiki/UK_railway_stations))

## Commands

 - `hubot: trains from <departure station> to <arrival station>` - Show the next trains from one station to the other
 - `hubot: trains to <arrival station>` - Show the next trains from the default station to the arrival station
