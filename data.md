# Band-Aide Data

### Top level
- users
- profiles (usually the same as the user, but user can have more than one)
- artists
- albums
- labels
- venues
- shows
- collaboration tracks
---

### User
- id 
- Name 
- Email
- Social media links
- Profile IDs

### Profile
- id 
- Name
- Image
- Blurb
- Bio
- Social media /links
- Artist IDs

### Artist
- id 
- Name
- Image
- Blurb
- Bio
- Social media /links
- Members (Profile IDs; optional)

### Album
- id 
- Label Release id 
- Name
- Image
- Blurb
- Description
- Artist IDs
- Tracks
- Label IDs
- Release Date/Year
- External links  or embeds (? BandCamp? Other...)

### Label
- id 
- Name
- Logo
- Blurb
- Bio
- Social media /links
- Artist IDs
- Album IDs

### Venues
- id 
- Name
- Logo
- Blurb
- Bio
- Social media /links
- Show IDs

### Shows
- id 
- Name (optional)
- Artist IDs
- Venue ID
- Date/Time
- All Ages/age limit
- Cost
- Link to tickets
- Poster

### Collaboration tracks
- id 
- Name
- Profile/Artist IDs
- Description including collaboration request details and ideas
- Embed
- Link to stems
- Private messages / public feed
