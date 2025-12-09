```mermaid
sequenceDiagram
  participant Browser
  participant Server
Browser->>Server: POST https://studies.cs.helsinki.fi/exampleapp/new_note_spa
Note right of Browser: New note is send to server
Note right of Browser: JS code fetched by initial loading of page, determines how the note is send to server and rerenders notes page in browser environment
