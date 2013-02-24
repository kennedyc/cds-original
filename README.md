CDs
=========

This is a service for keeping track of a personal CD collection.  It includes:

  - A list of CDs
  - CDs identified by ISBN number
  - Tracks for each CD
  - A list of CDs that contain artists, song names, release dates, titles, or any combination of these parameters
  - A list of genres
  - A concentration of CDs in a specific genre

Attribute values: id, class, name, and rel
-
id
-----------
  - list - Applied to a div tag.  The list of CDs in the collection.
  - genre - Applied to a div tag.  The genre or list of genres in the collection.
  - cd - applied to a div tag.  A CD and its tracks.

class
-----------
  - title - Applied to a form tag.  Search for album title.
  - artist - Applide to a form tag.  Search for artist.
  - song name - Applied to a form tag.  Search for song name.
  - release date - Applied to a form tag.  Search for a release date.

name
-----------
  - title - Applied to a form tag.  Add a CD title.
  - ISBN - Applied to a form tag.  Add an ISBN number.

rel
-----------
  - index Applied to an a tag.  A reference to the starting URI for the service.
  - stylesheet - Applied to a link tag.  A link to the CSS stylesheet.
  - genres - Applied to an a tag.  A reference to the list of genres.
  - query - Applied to an a tag.  A reference to the query form.
  - cd - Applied to an a tag.  A reference to a CD.
  - add-cd - Applied to an a tag.  A reference to form for adding CDs.
  - track - Applied to an a tag.  A reference to a track on a CD.
