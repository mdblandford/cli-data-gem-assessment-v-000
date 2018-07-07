Overview:

Group Exercise Class Schedule CLI will give the user the ability to access the group exercise schedules from each of the 5 metro Chattanooga (TN) YMCAs.  When the app is run, users will be greeted and asked to enter their preferred location. Upon the selection of a location, the user will then select between Land-Based or Water-Based Group Exercise Classes. That selection will in turn provide the user with the desired schedule.

The site being scraped is: https://www.ymcachattanooga.org/landwater-class-schedules

The GroupExerciseClassSchedule CLI will interact with the user. A ScheduleScraper will scrape the site, and a Schedule class will provide links to each of the potentially selected schedules.


Desired user interface:

YMCA of Metropolitan Chattanooga (TN)
  (1) Downtown
  (2) Hamilton Place
  (3) Cleveland
  (4) North River
  (5) North Georgia
    "For which YMCA location would you like the Group Exercise Class Schedule?
     Please enter 1-5."

    "For the "#{name}" YMCA, would you like the:
     (1) Land-Based Group Exercise Schedule
     (2) Water-Based Group Exercise Schedule
     (3) select a different location
     Please enter 1-3."

     A response of 1 or 2 will return a PDF
     A 3 response will return the user to the first menu
