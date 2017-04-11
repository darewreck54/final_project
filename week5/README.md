# Final Group Project- *Travel IT*

**Travel IT** is an android app that allows a user to plan a travel itinerary based on travels of a community of explorers that share their travel stories every moment as they embrace their travels, based on geo location.

Travel IT app creates a nice timeline view of each travel in addition to plotting the checked in locations for that travel nicely on a map. Travels could be made either public or private by the user that owns that travel log. Travel IT allows to share the full or partial travel log.

Mobile features:
* App utilizes camera to instantaneously take pictures as you travel and associate with a travel entry with ability to geo tag a picture.

* This app uses GPS to get the current location and to mark user's current location.

Key differentiators:
* App uses geo-fencing to send instant push notifications to travels based on several themes such as:
  * When other travelers have put a surprise locations such as hidden bars behind a large stairwell.
  * To monetize 3rd party vendors such as restaurants can request to add geo-fences when users are close to their location as notification appears saying that first drink is on the house etc.
  * Travels get hectic and we forget a few things all the time, this app could also remind you of certain side trips you could take when you are in the area.

## User Stories

The following **required** functionality is completed:

* [ ] The user would be able login via social login or via custom login.
* [ ] Leverage Firebase for backend, storing media content and push notifications.
* [ ] Should be able to view travel logs of a location, user's travel log entries in the form of a timeline with nicely laid out   markers on the map.
* [ ] Should be able to view a profile.
  * [ ] Should be able to follow a person.
* [ ] Bulletin board, where people can ask a question and other followers can comment on it
* [ ] User can **switch between Plan a Trip and Travel profile views**
  * [ ] User can view their upcoming travels or drafted itineraries.
  * [ ] User can view their travelled trips including images, videos that have be captured during a trip.
* [ ] Ability to capture an image or a small video and associate with the geolocation, time.
* [ ] Ability to search and discover places to see and eat based on other people's travel experiences.
  * [ ] Would be able to leverage 3rd party Apis like yelp/ trip advisor for reviews on a location.
* [ ] Should be able to search your own personal planned trip and where it is, in the reference to the map.
* [ ] Optionally direct messaging could be implemented to spur a private conversation between 2 or more parties to discuss a trip
* [ ] Implement geo-fencing with push notifications to surprise users as they enter a certain location on their travels.

The following **optional** features are implemented:

* [ ] Reminds travelers on some minor side trip items that one would like to do when they are in the area based on geo location. Optionally if the GPS is disabled or network is unavailable, reminders are driven by your pre-planned trip itinerary.
* [ ] Based on google's average time spent at a particular location create a cool auto draft of a travel itinerary based on the locations chosen.
* [ ] User should be able to click on any pins on the timeline map and be able to view the media content like pictures/ images taken.

The following **bonus** features are implemented:

* [ ] Tracks users location if user consents permission every so often and stores into the user profile. Later this location information could be used to show cool timeline of travel history and associate pictures/ videos taken on the timeline with the geographic map.
* [ ] Ability for registered 3rd party vendors to add geo-fences with realtime offers to be pushed to users who are in a vicinity of a certain location.

## Video Walkthrough


Here's the link to our project management, follow this board for realtime progress on our app [Trello Board](https://trello.com/b/T22jgcxq/exploreit-final-project)

Here's a walkthrough of implemented user stories:

<img src='https://github.com/darewreck54/final_project/blob/master/week5/gif/app.gif' title='Initial Flow of app' width='' alt='Video Walkthrough' />
<img src='https://github.com/darewreck54/final_project/blob/master/week5/gif/timeline_map.gif' title="Experimenting with timeline and maps" width='' alt='Video Walkthrough' />

This sums up the basic layout and structure we wanted to set up.  We were also experimenting with how to use timeline and maps which we will bring back into the project.


GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

Describe any challenges encountered while building the app.

## Open-source libraries used

- [Android Async HTTP](https://github.com/loopj/android-async-http) - Simple asynchronous HTTP requests with JSON parsing
- [Picasso](http://square.github.io/picasso/) - Image loading and caching library for Android
- [Gson](https://github.com/google/gson) - A Java serialization/deserialization library that can convert Java Objects into JSON and back.
- [Glide](https://github.com/bumptech/glide) - An image loading and caching library for Android focused on smooth scrolling
- [Parceler](https://github.com/johncarl81/parceler) - Android Parcelables made easy through code generation.
- [Butter Knife](https://github.com/JakeWharton/butterknife) - Bind Android views and callbacks to fields and methods.

## License

    Copyright [2017] [Derek Hang] [Sai N Muppa]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

### How do I get set up? ###

* Summary of set up
* Configuration
* Dependencies
* Database configuration
* How to run tests
* Deployment instructions

### Contribution guidelines ###

* Writing tests
* Code review
* Other guidelines

### Who do I talk to? ###

* Sai Muppa (snmuppa at gmail) or Derek Hang (darewreckk at gmail)
