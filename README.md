# Health-Tap
Created by Brian Yang and Hussein Fardous

# Our Health hack for 2018 DivHacks Hackathon

* Web app that contains pictures, where if you click on them, a function calls
    *Click on a phone picture that allows you to automatically 911
      * Twilio api
      *Has a dropdown menu stating the languages you speak, so a proper caller will answer
* Click on a robber picture in case someone breaks in and you can’t talk
    * Sends the location and message to emergency services
      * Twilio api
* Click on a hospital to show multiple subcategories of specialties
    * Eye, ear, general hospitals, ortho, neuro, cardiovascular,  vascular, pediatrician, dentist, psychological services
    * Once someone clicks on the picture, it’ll return the top 3 closest locations and the top 3 highest rating within the state
    * Route patients to the nearest and most cost-effective urgent care choice. Provide directions, travel time, wait times, insurance options, etc.
    * Once a location is press, there will be google maps navigation 
      * Google maps api

