# JCDS2504-Module-2-Capstone_Project
Capstone Module 2 Purwadhika
![image](https://github.com/user-attachments/assets/309d8e95-0b05-40d4-9c0e-7fc13d773f87)
![image](https://github.com/user-attachments/assets/291e295b-abef-47ef-9529-c7c20121c709)
# Data Dictionary

- `id`: Airbnb's unique identifier for the listing.
- `name`: Name of the listing.
- `host_id`: Airbnb's unique identifier for the host/user.
- `host_name`: Name of the host. Usually, just the first name(s).
- `neighborhood`: The neighborhood is geocoded using the latitude and
- `longitude`: against neighborhoods as defined by open or public digital shapefiles.
- `latitude`: Uses the World Geodetic System (WGS84) projection for latitude and longitude.
- `longitude`: Uses the World Geodetic System (WGS84) projection for latitude and longitude
- `room_type`: [Entire home/apt |Private room| Shared room| Hotel]
    - All homes are grouped into the following three room types:
        1. *Entire place*
            - Entire places are best if you're seeking a home away from
            home. With an entire place, you'll have the whole space to
            yourself. This usually includes a bedroom, a bathroom, a
            kitchen, and a separate, dedicated entrance. Hosts should
            note in the description if they'll be on the property or not (ex:
            "Host occupies the first floor of the home") and provide further
            details on the listing.
        1. *Private rooms*
            - Private rooms are great for when you prefer a little privacy,
            and still value a local connection. When you book a private
            room, you'll have your private room for sleeping and may
            share some spaces with others. You might need to walk
            through indoor spaces that another host or guest may occupy
            to get to your room.
        1. *Shared rooms*
            - Shared rooms are for when you don't mind sharing a space
            with others. When you book a shared room, you'll be sleeping
            in a space that is shared with others and share the entire
            space with other people. Shared rooms are popular among
            flexible travelers looking for new friends and budget-friendly
            stays.
- `price` Daily price in local currency. Note, the *$* sign may be used
despite the locale.
- `minimum_nights` The minimum number of night stays for the listing (calendar
rules may differ).
- `number_of_reviews` The number of reviews the listing has.
- `last_review` The date of the last/newest review.
- `calculated_host_listings_count` The number of listings the host has in the current scrape in
the city/region geography.
- `availability_365` The calendar determines the availability of the
listing x days in the future. Note a listing may be available
because it has been booked by a guest or blocked by the
host.
-  `number_of_reviews_ltm` The number of reviews the listing has in the last 12 months (cumulative).
