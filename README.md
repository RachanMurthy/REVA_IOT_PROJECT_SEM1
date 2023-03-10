# REVA_IOT_PROJECT_SEM1
Rachan Murthy	        (R22EK016)
Shreyas Y S           (R14EQ093)
Vishwas V             (R14EQ111)
Vivith Rajiv Kanchi   (R14EK023)

This code is for an Arduino sketch that interfaces with an Adafruit Fingerprint Sensor (R307) and WiFi module to enable fingerprint enrollment and verification through a Maker Webhooks IFTTT service.

The sketch includes four options:


Option 1: Verifies a previously enrolled fingerprint by prompting the user to place their finger on the sensor and then makes a web request to the IFTTT service.

Option 2: Enrolls a new fingerprint by prompting the user to enter their name and then enrolls their fingerprint using the R307 sensor. Once enrolled, the sketch makes a web request to the IFTTT service to register the new fingerprint.

Option 3: Deletes a previously enrolled fingerprint by prompting the user to enter the ID number of the fingerprint to delete.

Option 4: Deletes all fingerprints in the database by prompting the user to enter 'Y' to confirm deletion or 'N' to cancel the operation.


The sketch also establishes a WiFi connection to the specified SSID and password using the ESP32 WiFi module. The IFTTT service key and event names are defined as constants and used to construct the web request URL for each operation.
