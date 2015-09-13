# Hummingbird-Python
Wrapper/Handler for the hummingbird.me public api

## Plans For This Package
This is intended to be a fairly comprehensive Python wrapper for the Hummingbird web API, starting with V1, and then depending on how I feel, maybe maintaining a level of V2 operability.

The responses will of course be available in natural JSON, but the intended goal behind the whole thing is to object-ify all the returned library entries as Python objects, to make using the returned results easier on the user of the library.

## Current Progress
### Methods for V1
- [ ] Anime
  - [ ] Get Metadata By ID
  - [ ] Search by Title
- [ ] Library
  - [ ] Get All Entries
  - [ ] Add/Update Entry
  - [ ] Remove Entry
- [ ] User
  - [ ] Authenticate
  - [ ] Get Information
  - [ ] Get Activity Feed
  - [ ] Get Favorite Anime
