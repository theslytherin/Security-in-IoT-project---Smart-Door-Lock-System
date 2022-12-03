# Security-in-IoT-project---Smart-Door-Lock-System

This is a smart door lock system using a Raspberry-pi, a RFID reader, a webcam and a smart phone.
It gives 3-way authentication for residents as well as guest.

For Residents:
1. RFID tag
2. Registered pin
3. OTP on their phone.


For Guests:
1. QR code scan and message the resident
2. Approval from Resident after viewing the guests from their smartphones using a webcam
3. OTP on their phone

This could be acheived by using a twilio account for SMS sending, PHPmysql for storing the database and the access log.

