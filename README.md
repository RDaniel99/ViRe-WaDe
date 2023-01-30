# vire

## Problem description:

Build a (micro-)service Web system able to **"intelligently"** recommend – by exposing a **SPARQL endpoint** – vinyl music records according to various criteria: 

* user preferences (specified via controlled natural language constructs such as:
> "I always like/love/prefer classical music, especially opera music by Rossini or Verdi and performed by Angela Gheorghiu or Juan Diego Flórez; I sometimes like progressive rock and post-rock; I like only metal albums released before 2000; I always dislike/hate rap and hip-hop; I dislike songs produced by Flood in the last 25 years"
* past song purchases on various music stores 
* playlists – available online via music streaming services: [Last.fm](https://www.last.fm/api/webauth') and alternative solutions – and/or locally – for instance, by uploading a JSPF/XSPF document. 

The playlists could be created by the user or shared by her/his virtual "friends" (consider at least one social network). 

The system will use several music-related knowledge models (e.g., [Music Ontology](http://musicontology.com/) or [MusicRecording](https://schema.org/MusicRecording) concept from schema.org) and available public resources: [Discogs](https://www.discogs.com/developers/), [MusicBrainz](https://musicbrainz.org/doc/MusicBrainz_API), [Musicmoz Music Styles](https://vocabularyserver.com/music/).

## Design and arhitecture 
(for more commits check this repo: https://github.com/StativaCamelia/vire We just copied the info in this repository after the intermediate evaluation)
* Arhitecture of the web application:
* OpenAPI specification regarding the REST API – or, alternatively, a schema for the GraphQL API and Open API available in the technical report, all of them can be found in the report
* Technical report: https://rdaniel99.github.io/ViRe-WaDe/
* Project progress: https://github.com/RDaniel99/ViRe-WaDe/wiki/First-deliverable-status-page and the trello board: https://trello.com/b/cuiN0NpG/wade

