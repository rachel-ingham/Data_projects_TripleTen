# TripleTen Exploratory Data Analysis Project - NYC AirBNB Data

### The Prompt
Help a client analyze the Manhattan vacation rental market. They want guidance on which property types to invest in and you wukk analyze Airbnb data for insights. Make recommendations by answering the following questions: Which neighborhoods and property sizes are most attractive for vacation rentals?
and How much money did these listings generate?

### The Data
The AirBNB dataset was provided by TripleTen and includes 
- A Raw Listings Data spreadsheet containing  
    - Listing identifiers like `'listing_url'`, `'id'`, `'name'`, `'description'`, `'picture_url'` and more
    - Host information like `'host_id'`, `'host_name'`, `'host_location'`, `'host_listing_count'` and more
    - Neighborhood information like `'neighborhood'`, `'latitude'`, and `'longitude'` and more
    - Property information like `'accommodates'`, `'bedrooms'`, `'price'`, `'minimum_nights'`, and `'maximum_nights'` and more
    - Review information like `'number_of_reviews'`, `'first_review'`, and `'reviews_per_month'`and more
- A Raw Calendar data spreadsheet containing
    - `'listing_id'`
    - the `'date'` in the listing's calendar
    - whether the date is `'available'` for booking
    -  the `'price'` listed for the day and the `'adjusted_price'`
    -  the `'minimum_nights'` and `'maximum_nights'` for a booking made on this day

### The Process
After some basic data cleaning, I created pivot tables to analyze which neighborhoods and property sizes are most attractive for vacation rentals based on reviews in the last month. To calculate how much money the most attractive listings generated, I focused on the top 10 neighborhoods and the most popular-sized property in those neighborhoods by creating a top_listing identifier column. Annual revenue was estimated by multiplying the last month's revenue by 12. 

### Results
- Midtown studio rentals and 1 bedroom rentals in neighborhoods like Harlem, Lower East Side, Hells Kitchen and Upper West Side are popular among travelers and have the most 
reviews in the last month. Of these popular rentals, studios in Midtown and 1 bedrooms in the Lower East Side, Chelsea, and Hells Kitchen are the top revenue earners.
- The top-earning listing had an estimated annual revenue of $359,280 and is listing ID 49946551, a Midtown apartment that sleeps 6 people.
- Based on the data analysis, I would recommend that my client find investment properties that are 1 bedroom units in the high earning and frequently visited neighborhoods of Lower East Side and Hells Kitchen, or studio units in Midtown.

### Project Link
https://docs.google.com/spreadsheets/d/1E9-ddjDwhBZvqtepdUmKIcqcb04v2ThdlD-h_ymHd38/edit?usp=sharing
