BidarRide Driver Navigation Helper

File: driver.html

What it does:
- Driver enters pickup and destination from the confirmed WhatsApp booking.
- "Navigate to pickup" opens Google Maps directions to pickup.
- "Arrived at pickup — Start Ride" opens Google Maps directions to the drop-off from the driver's current location.
- "Complete Ride" displays a reminder to notify the booking team.

How to publish:
1. Open the GitHub repository used for https://avinashghode1718-wq.github.io/BidarRide/
2. Upload driver.html to the repository root (the same folder as index.html).
3. Commit the change.
4. Open https://avinashghode1718-wq.github.io/BidarRide/driver.html

Important limitations:
This static helper does not connect to a live driver assignment database, detect arrival automatically, or update ride status centrally. The driver must copy the pickup/drop locations from the existing WhatsApp booking. Google Maps provides turn-by-turn navigation.
