### [LocalMotion]

#### Pitch

The Kayak of local travel.
See all ride sharing options in your immediate area.

#### Description

The emergence of numerous community-based transportation options such as ride
sharing is great but with people having memberships to many services, it is
difficult to compare and choose the best option at any given time and location.

This app will aggregate all Denver ride sharing options within a one to two mile
radius of the user such as Uber, Lyft, B-Cycle, and Car2Go.  The results will be
filterable by distance &&/|| price and show the best route between the user and
their final destination.

#### Target Audience

This application will be geared toward Denverites who take advantage of local
travel ride sharing options and attempt to maintain a low-carbon footprint.

#### Integrations

* [What OAuth provider makes sense for this audience?]
  Uber OAuth

* [What Data.gov data or API will you use?]
Uber API, Car2Go API, B-Cycle API

* [Any other integrations?]
Google Maps


### [LocalFlea]

#### Pitch

Tinder of Craigslist
Uncover local treasures right around you from the comfort of your own home.

#### Description

Craigslist is an awesome tool for buying items from people around you yet is only
good for when you know what you're looking for.  People love flea markets because
they love a deal and they love to peruse.  LocalFlea aggregates listings of sale
items in your neighborhood and presents them in an easy and fun UI. You're only
served one listing at a time so you can flip through what's out there.  Over time
the algorithm learns what you like and notifies you of great finds.

The app will pull in listings from (Craigslist? Ebay?) and serve each one individually
along with how far away it is.  It will also cross-reference Ebay for average
asking prices on the items you find.

#### Target Audience

People who enjoy local community interactions and like to browse yard sales and
flea markets from the comfort of their own home.

#### Integrations

* [What OAuth provider makes sense for this audience?]
  eBay OAuth

* [What Data.gov data or API will you use?]
http://data.denvergov.org/dataset/city-and-county-of-denver-statistical-neighborhoods

* [Any other integrations?]
Google Maps


### [TourBrew]

#### Pitch
Your personal brewery tour guide.
Custom walking tours of Denver microbreweries.

#### Description
Denver is a hotspot for microbreweries with new ones popping up constantly.  
TourBrew.co shows users a map of all the breweries and how old they are. Users
can then select what kind of beers they are interested in and get a tailored
walking beer tour to different breweries.

#### Target Audience
Denver microbrewery enthusiasts and visiting beer aficionados.

#### Integrations

* [What OAuth provider makes sense for this audience?]
  FourSquare OAuth

* [What Data.gov data or API will you use?]
http://www.brewerydb.com/developers
http://www.denvergov.org/maps/map/liquorlicenses

* [Any other integrations?]
Google Maps


### [Altruity]

#### Pitch

Your one stop shop for local volunteering opportunities.

#### Description

Altruity is your place to go if you're interested in making a difference in
your local community in new and exciting ways.  
**MVP**: Altruity allows users to put in their interests, skills, and availability
to see a map of opportunities.  You can see pictures of the place and of the
people who will be there to help when you are.
**Future**: Charities/organizations can claim their listing and maintain their
level of need, upload pictures. Users earn badges and hours through the site
(even though that defeats the purpose of altruism).

#### Target Audience
Altruistic individuals hoping to make a difference in their community.

#### Integrations

* [What OAuth provider makes sense for this audience?]
  FourSquare OAuth for checkin? may find charity OAuth?

* [What Data.gov data or API will you use?]
https://catalog.data.gov/dataset/benefits-gov-volunteer-opportunities-benefits

* [Any other integrations?]
Google Maps


### [UrbanGardenClub]

#### Pitch
Urban Garden Club creates an online community around local urban gardens.

#### Description

UGC maps all the urban gardens around Denver and provides a sense of community
arund them.  UGC has pictures, what plants are growing, and who is helping
plant and tend crops. UGC allows for intergarden bartering of crops as well.

#### Target Audience
People with a green thumb and sense of community.

#### Integrations

* [What OAuth provider makes sense for this audience?]
  Facebook for identity gleaning

* [What Data.gov data or API will you use?]
http://data.opencolorado.org/dataset/city-and-county-of-denver-zoning-for-urban-gardens
http://data.opencolorado.org/dataset/city-and-county-of-denver-zoning-for-primary-food-sales-or-markets
http://dug.org/garden-list

* [Any other integrations?]
Google Maps


### [Errandr]

#### Pitch

Running errands is a pain, group them all in an easy to follow route with Errandr.

#### Description

Errandr is the app to use when you have errands to run.  Simply put in which errands
you need to run out of common errands: gas, bank, grocery, post office, etc.
Errandr will select the best route for running all your errands and is smart enough to
add personalized errands as well as stack tasks accordingly (like getting groceries
last).

#### Target Audience
Busy people who like efficiency.

#### Integrations

* [What OAuth provider makes sense for this audience?]
Amazon OAuth

* [What Data.gov data or API will you use?]
grocery: http://data.opencolorado.org/dataset/city-and-county-of-denver-food-stores
post: https://www.usps.com/business/web-tools-apis/welcome.htm
fuel (gas): http://www.mygasfeed.com/keys/api
fuel (electric): http://data.opencolorado.org/dataset/city-and-county-of-denver-electric-vehicle-charging-stations

* [Any other integrations?]
Google Maps

```
## Other Idea Dump:

-I would really like to build out an app that aggregates events around a local
area on a given day/night; a little overdone but I would find it very interesting.
I also liked the 'Yelp for Local Art' idea as it was very similar to one I had,
but the gov data is old and stale; I would like to identify new art galleries,
exhibits, art events, and artistic agencies (graphic design, web design, app, etc.).

-People around the nation (and world) are looking to CO to see the effects of
legal marijuana sales.  This app will track marijuana sales, points of heaviest
sales juxtaposed against areas of crime, as well as points of marijuana tax
related spending.
http://data.opencolorado.org/dataset/city-and-county-of-denver-marijuana-sales-tax
```


[LocalMotion]:http://www.localmotion.co
[LocalFlea]:http://www.localflea.com
[TourBrew]:http://www.tourbrew.co
[Altruity]:http://www.altruity.org
[UrbanGardenClub]:http://www.urbangardenclub.com
[Errandr]:http://www.errandr.com
