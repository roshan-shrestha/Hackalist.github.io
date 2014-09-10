![hackalist-logo](images/logo.png)
=================================
Visit our [website](http://hackalist.org) to view the live site.

Hackalist is a database of hackathons that has the most up to date information for all your hackathon needs.

Feel free to submit [Pull Requests](http://github.com/Hackalist/Hackalist.github.io/pulls) and/or [Issues](http://github.com/Hackalist/Hackalist.github.io/issues).

If you have any questions or concerns, please tweet [@KevinPayravi](http://twitter.com/KevinPayravi).

Authorship
=================================
Site initiated by [Kevin Payravi](http://www.kevinpayravi.com/). Special thanks to:
* [Aaroh Mankad](https://github.com/aarohmankad) for implementing Bootstrap and automated AngularJS parsing.
* [Rodrigo Argumedo](https://github.com/rodrigoargumedo) for continued support.
* All others who have submitted hackathon listings.

See the [list of contributors](https://github.com/Hackalist/Hackalist.github.io/graphs/contributors) for all contributors to the project.

API
=================================
The Hackalist API is split into separate JSON files for each month of each year, following the file pattern "/api/1.0/YEAR/MONTH.json":

##2014
* August - http://www.hackalist.org/api/1.0/2014/08.json
* September - http://www.hackalist.org/api/1.0/2014/09.json
* October - http://www.hackalist.org/api/1.0/2014/10.json
* November - http://www.hackalist.org/api/1.0/2014/11.json
* December - http://www.hackalist.org/api/1.0/2014/12.json


##2015
* January - http://www.hackalist.org/api/1.0/2015/01.json
* February - http://www.hackalist.org/api/1.0/2015/02.json
* March - http://www.hackalist.org/api/1.0/2015/03.json
* April - http://www.hackalist.org/api/1.0/2015/04.json

##Parameters
* `title`: Name of hackathon
* `url:` Official URL
* `startDate:` Starting date in "Month Day" format (e.g. August 30)
* `endDate:` End date in "Month Day" format (e.g. August 30)
* `year:` Year
* `city:` City hackathon is occuring in.
  * If in U.S., format as "City, State Abbraviation" (e.g. Miami, Florida).
  * If elsewhere, format as "City, State/Province Abbreviation, Country Name" (e.g. Toronto, ON, Canada).
* `host:` The host (university, company, etc.)
* `length:` Length in hours
* `size:` Number of attendees; if not known, specify "unknown"
* `travel:` Is travel reimbursed, in either part or full? yes | no | unknown
* `prize:` Are prizes awarded to winners? yes | no | unknown
* `highSchoolers:` Are high schoolers allowed to apply or attend? yes | no | unknown
* `facebookURL:` URL to official Facebook profile
* `twitterURL:` URL to official Twitter profile
* `googlePlusURL:` URL to official Google+ profile
* `notes:` Any additional notes (limits to who can attend, special requirements, etc.)


##Notes
When adding to the list, please keep the following points in mind:
* Listings are sorted chronology based on the starting date of the hackathon.
* If two hackathons start on the same day, they are sorted alphabetically.
