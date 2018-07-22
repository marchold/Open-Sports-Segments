# Open-Sports-Segments
Open source distributed database of sporting segments for people to do GPS based cycle and running races. The purpose of this is to provide an open source alternative to comercial solutions currently available.

## Backend requirements
 * Store user records on a public blockchain with users existance being verified by other users.
 * Segment data will be stored as a compressed polyline encripted with a user owned key 
   * Segments must be indexable by region such that its easy to download segments for an area
 * Activity files (fit files) will be stored off chain but the data in them will be parsed and verified by other users
   * Segment efforts will be created from the activity file
 * Segment efforts must be able to be easily associated with segments
  
 
## Frontend requirements
 * Users should be able to extract polyline segments and create segments
 * Users should be able to get other users segment efforts for segments they are intrested in
 * Users should be able to submit activities as fit files and have their segment efforts made public
 
 
