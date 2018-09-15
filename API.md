 # Nodes
 Master nodes will hold a full copy of all the data while light nodes will hold only a subset of the data that they are using.

 ## Master Nodes API
 All API calls will have a "since" date parameter indicating a timestamp when we have data for
  * Peer managment
    * Get peers list
    * Add new peer 
    * Update peer data
  * Athlete managment  
    * Register user identity data
    * Update user identity data
    * Get athlete activities
    * Get athlete segment efforts
  * Activity managment
    * Add new user activity
    * Verify/Flag user activity
  * Segment managment
    * Get segments
    * Add segment
    * Update segment
  *  
    

### Athlete managment::Register user identity data
A users identity is a public key. The user must maintain a copy of their private key in order to submit any new data or alter existing data. Once a public key for a user has been submitted it can not be removed. When a user creates an activity with efforts in it and other users see the data they other users can sign the data. When signing someone elses data a user can mark it as known authentic or not authentic. 

### Activity managment::Add new user activity
A user signs a new activity record with a summary of the activity including a compressed polyline and a timestamp sequence to go with it. A users activity record will also contain segment summaries for the activity.
