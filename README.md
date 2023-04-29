# system-design

LLD of BookMyShow

Action Plan:

1: Write/Gather Requirements

2: Who are the actors/users

3: Set Sequences and Activities for every actors/users

Note :  Write all features for different users, few features can be specific to users and few can be common for all users/actors.
        Start with basic features with consideration of extensibility and scalability

1st User/Actor : Common user/costomer(Who will book the shows)

                 Login (Common for all)
                 Location access (Specific to common user/customer)
                 Dashboard with available shows (based on selected location)
                 Any recommended shows/events
                 Search by show name/theatre name/category
                 Show/Event Detailed page (will contain all details for any selected show/event)
                 Book ticket from show details page
                 Selecting any specific specific details before booking (like language/screen/date/showtime/theatre/price/number of tickets/seat location)
                 Making payment using CC/GC/UPI/Internet Banking
                 Getting booking confirmation details
                 Access of Profile info to view/update the details
                 Access of booking history and option to download any upcoming booking confirmation details
                 Can give review to any booked event/show


2nd User/Actor : Cinema/Show Owner (Who will schedule shows/events)

                 Login (Common for all)
                 Profile info for any event manager/theatre owner (they can manage all info regarding the theatre or there event company)
                 Dashboard to manage (add/update) any show/event info (event date/timing/available slots/location/language/price/screen)
                 Dashboad with details of any specific hosted events with all latest details (number of ticket booked/total revenue generated/rating received)
                 Option to manually update available slots/booking info (if any other way possible to book same event/show)


3rd User/Actor : System (To handle common events and make application operable)

                 Notification Manager
                 Payment service to accept and authorize any transactions
                 Recommendation service based on selected location and previous booking history
