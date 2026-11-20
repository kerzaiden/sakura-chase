# Sakura Chase

A small phone web app for Keren and Gabush's trip to Korea and Japan, 13 to 29 April 2027.

- **Today:** countdown and pre-trip checklist, then the day's plan, local and Tel Aviv time, hotel, and map links.
- **Plan:** all 17 days by city.
- **Stamps:** a stamp book of experiences to collect.
- **Money:** expense splitter and currency converter.
- **Say it:** Korean and Japanese phrases to show locals, plus emergency numbers.

It's one self-contained `index.html`, served with GitHub Pages. Data is stored in each phone's browser. To sync two phones, tap the cloud button, paste a fine-grained GitHub access key limited to this repo (Contents: read and write), and send the sync link to the other phone. Synced data lives encrypted in `trips/` on the `sync-data` branch; the encryption key exists only inside the sync link, so share that link only with each other.
