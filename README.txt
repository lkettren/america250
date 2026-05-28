
Pinewood Derby Interactive Map - Version 2
=========================================

Files in this package:
- index.html
- A250 Map Online Version.png

What this version includes:
- Clickable booth and feature overlays
- Right-side detail panel
- Search box
- Jump menu
- Direct-link support using URL hashes (example: #A1)
- Responsive layout that works well when embedded into Google Sites with an iframe

How to customize assignments:
1. Open index.html in a text editor.
2. Search for the block named customAssignments.
3. Replace the sample entries with your real assignments.
   Example:
   A1: {
     title: 'Pack 999',
     description: 'Blue & Gold display',
     notes: 'Awards table next to booth',
     status: 'reserved',
     contact: 'Jane Doe'
   }

Valid status values:
- open
- reserved
- feature

Recommended hosting options:
- GitHub Pages
- Any static web server
- A shared web host that serves plain HTML files

Embedding in Google Sites:
1. Host the files so index.html has a public URL.
2. In Google Sites choose Insert > Embed > By URL.
3. Paste the public URL for index.html.

Coordinate tuning:
The booth overlays are based on the uploaded floor plan and use adjustable constants near the top of the script in index.html.
If you want tighter hitboxes, adjust the LAYOUT object values.
