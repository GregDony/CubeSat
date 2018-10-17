### Responsibilities
* Processing and storing housekeeping data (i.e. telemetry) and payload data (images)
    
    This entails:
    * Deciding on SQL or noSQL for the database
    * Designing the database (relations, structure)
    * Determining where the data will be stored (i.e. cloud provider?)
* Displaying the data

    This entails:
    * Developing a secure log-in portal with two-factor authentication where the telemetry data can be viewed
    * Developing an intuitive and clear interface for viewing housekeeping/telemetry data
        * Will need input from each subsection on what values they require
    * Including a visual representation of the location of the CubeSat while in orbit (important for outreach!)
    * Determining how to uncompress the payload data for display
        * The payload uses proprietary software for image compression prior to downlinking the data
* The ability to send telecommands to the CubeSat

    This entails:
    * Interfacing with the Ground Station team
        * What hardware devices are sending the commands and how do we interact with them?
    * Interfacing with the Onboard Data Handling team to determine the command formats
        * Dependant on RAM (i.e. must the commands be long and explicit or can they be short and have their intended functionality determined onboard)
    * Having an input area such as a dropdown menu of telecommands to choose from, with fields for flags, etc.
        * All values must be checked before sending
    * An admin user should be able to update the list of available telecommands
* Developing an alert system to notify of data values exceeding the nominal limits
* Developing an automated anomaly logging system
