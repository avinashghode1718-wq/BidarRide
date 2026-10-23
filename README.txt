BidarRide location upgrade

Includes:
- Use my current location button for pickup (browser permission required).
- Search pickup and destination by place name and choose a result.
- Sends selected coordinates as Google Maps links in the WhatsApp booking message.
- Manual landmark typing remains available as a fallback.
- WhatsApp booking number remains +91 97401 00189.

Update the live GitHub Pages site:
1. Download and extract this ZIP on your phone.
2. Open your GitHub repository: avinashghode1718-wq/BidarRide.
3. Tap Add file > Upload files.
4. Upload the included index.html to the repository root and confirm replacing the existing index.html.
5. Commit changes. GitHub Pages will redeploy automatically; wait a few minutes, then refresh the site.

Important:
- GPS works on HTTPS and only after the customer gives browser permission.
- Search requires an internet connection. If search fails, customers can type a landmark manually.
- This prototype uses user-triggered OpenStreetMap Nominatim search/reverse-geocoding with low-volume use and attribution. Its public service has strict limits and is not guaranteed for a growing commercial ride-booking service; switch to a suitable commercial geocoding provider before scaling.
- WhatsApp opens a prefilled message; the customer still taps Send. Ride and fare require manual confirmation.
