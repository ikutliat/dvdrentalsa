# Introduction #

Dvd Rental Website


# Details #

DVD portal
# -=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=- #
Vision:

We want to establish a single online portal where people will go when they want to rent a DVD. This portal will empower DVD rental shops, in that they get access to the web, as well as (when we're the most popular DVD rental portal in SA) access to every potential customer who's looking for a DVD via our website. In short, we want to become the place where people go if they want to rent a DVD.

What will make this portal unique:
(a) People can rent a DVD from the comfort of their own homes
(b) People can immediately see whether or not a DVD is available at a particular shop (saves them driving to the shop and spending x minutes looking for alternatives they didn't really want)
(c) Gives immediate access to thousands of reviews and ratings for a particular movie (links to rottentomatoes, IMDB etc)
(d) Gives customers the ability to book a DVD well in advance
(e) When SA's bandwidth allows it (which may be sooner than we think), this can possibly turned into a live netflix type streaming service where people watch movies online
(f) option to post a message on their fb/twitter page, saying they just rented a DVD from "dvdrentalsa.com"
# -=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=- #
What is required:

(a) website (very similar to ster-kinekor's).
  * Website should allow customers to quickly navigate to and see DVD shops in the town/area where they live. Maybe incorporating google maps with exact location  of every DVD shop in our database?
  * customers should be able to type the name of a movie and see which shops have it (a) in stock and (b) if they're available or not (ie, rented by someone else or not)
  * if a DVD shop is offline, they should not appear in our results
  * preferably written in something like html5
  * mysql or similar (free) database
  * NB NB NB: the overall user experience must be extremely slick and fast (ie, determine if bandwidth high or low and depending on that only display movie names or images eg). Intelligent back end that predicts what people look for (we get the most queried info ready and display it instantaneously when asked for)

Main page options:

- Select a DVD shop: (drop down list that adapts to options, based on choice. First option province, then town, then specific shops. Only show online shops)
- Search for a movie: (searchbar where users can type the name of a specific movie. Google instant type feedback would be great, if bandwidth allows it)
- Select a movie category: (iterate through different options so people can search for particular movies. When a particular movie has been selected, use should be able to click a "book at my DVD store" button, which then goes through the same process as "Select a DVD shop", but only showing shops which have this DVD (with shops not having it available for today a lighter shade or something)
- register a new DVD shop: DVD shop owners can click here to (a) download or free software and (b) register their business. For now, I think we should verify each business ourselves (or appoint someone to do it). So they download and install the software and get a code to link their shop to our database as soon as they've been verified)

(b) client based software:
  * initial thought was to provide an API that works with standard DVD rental software. Easiest would be to create our own and make it freely available. This software should thus work as a standalone package (providing all the functionality current software allows), but stay in sync with our servers and database when online. A DVD shop will thus never be obliged to make use of our online service (option to disconnect, should they want to).
# -=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=- #

How we make our money?

**5% of every DVD booked through our website.  Possibly Google adds at some stage.** hope someone like Google or Microsoft of Netflix buys us
