Tasker
======

Collection of Tasker tasks. Most tasks have been inspired by others either via direct xml export or by description and recreation.
This task collection is licenced under the MIT License (see LICENCE for details).
##### Some tasks require secure settings (with root) or other listed plugins

#### Location
======
* Message recieved from any contact with contents "GPS":
    * Enable GPS
    * Get Location
    * Respond to sender with message that contains:
        * "Location %LOC. Accuracy: % LOCACC. Battery Status: %BATT"
    * Create notification that includes:
        * Who the response was sent to
        * The time that the response was sent
        * The location that was given as a response
    * If Variable GPSInUse is false than turn off GPS
        * GPSInUse is defined as true while specified apps are open (such as maps)

* Wifi (Home Network) Detected:
    * Set variable isHome to "true"

* Wifi (Home Network) Not Detected:
    * Set variable isHome to "false"
