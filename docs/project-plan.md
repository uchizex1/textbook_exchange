# Project Plan: Gator Textbook Exchange

## Who is the user?
UF students who are looking for used textbooks for a specific course. It can be a difficult to find the right edition at a fair price due to unorganized listings and comparing across multiple sites, so students end up wasting time or overpaying.

## User input
- Course code (e.g. MAC2313)
- Textbook Edition (e.g. 10)
- Price Range (e.g. $50 - $100)
or
- ISBN (e.g. 123-4-56-789012-3)
- Price Range


## App Output
A list of listings, the top ones being the closest match that include short explanations of why each listing ranked where it did.

## What does the software decide?
The most suitable listings for the students 

## The Main Algorithm
Listings are matched by course and price range, then are ranked by edition match, price, and item condition.

## Success Metric
10 test buyers find what they need in the top 3 listings searched.

## Edge Case
- No listings match
- Duplicate listings
- Listing without a price or edition

## Data
A hand-made file of 20-30 fake listings (data/listings.json)

## What am I intentionally not building
- Real payments
- Real listings
- User logins
- Real seller reviews