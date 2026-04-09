## Problem Statement 
A large convention venue hosts Comic-Con India, where thousands of visitors arrive across multiple days for anime screenings, cosplay competitions, gaming showcases, creator meetups, merchandise zones and panel discussions.

During the event, people arrive using bikes, cars, SUVs, cabs and EV vehicles. The venue has a structured parking facility divided into multiple zones and levels. Some parking areas are reserved for cosplayers with props, exhibitors, creators, VIP guests, staff members and EV charging vehicles.

Whenever a vehicle enters the parking facility, the system generates a parking ticket and assigns a suitable parking spot depending on vehicle type and availability. When the vehicle exits, the system records exit time and calculates the parking fee.


### ERD should include the important structures needed for:

vehicles

vehicle categories

parking spots

parking spot categories

parking zones or parking levels

parking tickets

parking sessions (entry and exit tracking)

payment records

### Things to think about:

one vehicle can enter multiple times during the event

one parking spot can serve many vehicles over time

parking sessions should store entry and exit timestamps

tickets and parking sessions may be separate structures

different vehicle types require different parking spot types

some parking spots may be reserved

parking availability must be trackable

zones or levels may contain multiple parking spots

payments should be connected to parking sessions

avoid putting everything into one single entity

### Entities :
1. vehicle
2. vehicle_types
3. access_category
4. parking_zone 
5. parking_spot 
6. spot_type
7. spot_allocation
8. parking_ticket
9. parking_sessions
10. payment
