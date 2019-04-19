# Proximate - Using W3.CSS Framework
**Author:**<br>
Anika Neela<br>

**Website Description:**<br>
It is a web app that enables the users to find and offer services within their
local communities as well as anywhere around the world, if they may choose to
do so. The website aims to not just reach the primary goals of the user, but also to
facilitate the process by implementing considerate design patterns. <br>

**#Primary persona goals addressed:**<br>
• The user can achieve their goals using the mobile app/web app in their cellular
device.<br>
• They can use the app to find and/or offer services within their local
communities. <br>
• The app provides ‘Profile’, ‘Review’, ‘Share’ and ‘Offer Service’ features that
enables the users to promote their services to other users.<br>
• It is a web-based solution to address the user’s needs from this product. <br>
• The service results default to local communities which can be further
controlled by restricting the amount of areas (in miles) the user is hoping to
find the service provider from. Ex- The user can further narrow down her
search to find a service provider within 0.5 miles of her location. <br>

**#Prerequisites:**<br>
-Languages used: HTML5, CSS, JS, JQuery<br>
-Software: Notepad++ <br>
-Framework: [W3.CSS](https://www.w3schools.com/w3css/) <br>

**#Goal of the project:**<br>
To implement a new framework for prototyping during crunch-time for the stakeholder.

## Design Patterns/Principles:
The design patterns used in the product are:<br>

**(1) Be Perceptive**: The product is perceptive of the user’s needs by providing
features and operations that the user needs.<br>
a. Schedule: Enables the user to keep track of the services they have
booked for the current date while keeping track of the services that
have been provided with in the past.<br>
b. Message/Call: Enables the user to directly message or call the service
provider if they choose to discuss few specifics about the service or
to communicate in general.<br>
c. Favorites: Enables the user to mark something as favorite if they like
a service and wish to come back to it later.<br>

**(2) Be confident**: The product is perceptive to enable the users to roll back any
changes they have made so far.<br>
a. Unbook: Enables the user to unbook any services they have booked.
(Note: Validation will be in place to ensure that the unbook option is
not triggered if it is a past record or if there is less than 24 hours for
the service to take place. It is because we want to respect the service
provider’s schedule while giving the user the freedom to back off if
they choose to do so. Not to mention, our consumer is also a
potential service provider, so it is a win-win for both in that aspect.)<br>
b. Edit or Undo: To err is human so the users can go back to edit their
information or undo their actions.<br>
c. Back or Exit: The user is given the freedom to navigate to back to
their previous page or exit any screen if they choose to do so.<br>
d. Home: The user is almost always able to navigate to the home page
from any page using either the company logo or the home icon at the
bottom left panel of the screen.<br>

**(3) Put the shoppers in control**: Enables the user to remain in control of their
finding/offering service experience without being dictated of how to
navigate around the app. They are also given multiple ways to land on the
same page, without enforcing them to follow one strict process for certain
pages.<br>
a. Location Filter: Although the app defaults to the user’s current
location in respect for the primary persona’s goals, it still does allow
the users to narrow their search in terms of miles as well as broaden
their search to any address, if they may choose to do so. <br>
b. Date & Time Filter: This filter enables the user to choose a particular
date as well as select which part of the day they want to find a
service for. Ex- Morning, afternoon, anytime.<br>
c. Search and Tiles: Enables the users to navigate through service
results using tiles or search.<br>

**(4) Keep it human, stupid**: Aims to ensure the product serves human nature
through multiple features:<br>
a. Sign-In/Sign-Up: The screen is kept familiar while asking for minimum
information for the users to fill up to sign-up/sign-in. It also allows
the users to sign-in with other popular social media accounts like
Facebook and Google.<br>
This app understands that not everyone who gets this app wants to
have an account here. Thus, we made payment option and sign-up as
optional features until the user attempts to book or offer a service.
The whole point we are doing so is to ensure that the user can scout
through the services and make an informed decision if they even
want to receive services from the enlisted service providers.<br>
b. Prefill and Required Fields: The important fields are marked with
asterisk and the unimportant ones can be filled in some other time or
not at all, depending upon the user’s choice. Moreover, the app is
smart enough to prefill information depending on the info provided
in other screens so far (except sensitive data if not saved). For
example, if the user signs in with Facebook, the username field,
although optional, is filled in by the app with the Facebook’s profile
name. Another instance is in the Offer Service screen when the user
is trying to create a post to provide a service, most of the info can be
prefilled from the account information except for price and service
info, which are required.
(Note: The user is given the option to edit the info as well).<br>
c. Notifications: Understanding that our users may have a busy life, by
default the app takes the responsibility to alert the users when the 
service they have ordered is about to take place. Being said that, the
users can customize this experience by going to the Schedule feature
and changing how far before the scheduled service they want to be
notified and if they want to be notified at all.<br>
d. Navigation: Although the users are asked when a service scheduled
for them had taken place to provide a customer review (optional),
the user is not at all expected to remember the service provider at a
glance. Thus, the review page allows the users to land into the
details/profile page for the service provider if they intend to do so.<br>
e. Defaults: Although the app provides the users with some control over
their experience, it still takes some liberty to make few smart
deductions for defaults. For example, the search results are always
listed being ordered by the highest rating and the cheapest price.

## Scenarios:
**❖ Offer Service:**<br>

o Context/Overview: <br>
The primary persona, Molly, can use the app in
her mobile device and post one or more services that she is
interested to offer and then post those services for others to see in
the app. Molly can post her service any time of the day with service
details. Once the other consumers are interested in Molly’s services,
they will book an appointment with her which will get directly into
her Message/Inbox, giving her the option to accept or deny the
appointment, like the Microsoft Outlook appointment request. Once
she accepts the request, it gets directly added to her schedule so that
the app can remind/notify her when appropriate.<br>

o Primary Interaction Flow:<br>
**▪ User is not logged in, nor is their payment option set:**<br>
• Clicks on the Offer Service tile from the home page.<br>
• Gets prompted with sign in screen as well as payment
option screen.<br>
• Fills up the required information and submits.<br>
• The user is then directly taken to the Offer Service page.<br>
• User name and phone number is prefilled from the
profile set-up so they can fill in the required service info
and hit the ‘Post Service’ button.<br>
• The user is taken to the home page with a banner
fading-in showing that their service has been
successfully posted.<br>

**• In Short (Navigation):** Home page > Offer Service tile>
Sign in page> Payment Option page> Offer Service page
> Post Service button > Home page with visual feedback
for confirmation> END.<br>

**User is logged in and their payment option is set:**<br>
• Clicks on the Offer Service tile from the home page.<br>
• Lands on the Offer Service page.<br>
• User name and phone number is prefilled from the
profile set-up so they can fill in the required service info
and hit the ‘Post Service’ button.<br>
• The user is taken to the home page with a banner
fading-in showing that their service has been
successfully posted.<br>

**• In Short (Navigation):** Home page > Offer Service tile>
Offer Service page > Post Service button > Home page
with visual feedback for confirmation> END. <br>

**❖ Find Services:**<br>

o Context/Overview: Molly can browse or search through the app to
find services of her choice. Although Molly is not restricted from
browsing and searching any services without signing-in, Molly is
required to sign-in before booking an appointment for her desired
service. Once she books a service, she has the option to unbook it
within 24 hours before the service takes place or before the service 
provider accepts her request. The service then gets registered in her
schedule which then notifies/reminds her when appropriate.<br>

o Primary Interaction Flow:<br>
▪ User is not logged in, nor is their payment option set:<br>
• User clicks on the Find Service tile from the home page.<br>
• Either searches or clicks on a tile (ex- cleaning) to see
the results for that service type.<br>
• The search results are by default of the user’s local
communities which can be changed by the user by
manipulating the filters.<br>
• The user scrolls through the result and gets a peak at the
preview of the service, for instance, service provider
name, service price, and ratings. Alternately, the user
clicks on the preview to go to the details page, from
where they can book as well.<br>
• The user can directly hit the Book button to request the
service and a banner appears to give visual feedback.
[Note: The user is not allowed to book the service even
when the Book button is pressed in this case and is
taken to the sign-in and payment option screen to fill
those first. Once filled in, the service is booked.]<br>
• The service, once accepted by the service provider, gets
registered in the user’s schedule and notified when
appropriate.<br>

• In Short (Navigation): Home page > Find Service tile>
Find Service page > Book button > Sign-in>Payment
Option> Booked!<br>

▪ User is logged in and their payment option is set:<br>
• User clicks on the Find Service tile from the home page.<br>
• Either searches or clicks on a tile (ex- cleaning) to see
the results for that service type.<br>
• The search results are by default of the user’s local
communities which can be changed by the user by
manipulating the filters.<br>
• The user scrolls through the result and gets a peak at the
preview of the service, for instance, service provider
name, service price, and ratings. Alternately, the user
clicks on the preview to go to the details page, from
where they can book as well.<br>
• The user can directly hit the Book button to request the
service and a banner appears in that very screen to give
visual feedback of their action.<br>
• The service, once accepted by the service provider, gets
registered in the user’s schedule and notified when
appropriate.<br>

• In Short (Navigation): Home page > Find Service tile >
Find Service page > Book button > Booked!

