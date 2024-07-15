This web application allows users to convert speech to text and save the recognized text to a database using a simple interface.

Setup:

Start Recording:
* Click on the "Start Recording" button (represented by a play icon) to begin speech recognition.
Recording Speech:
* Speak into the microphone connected to your device. As you speak, the recognized text will appear in the text area. Finalized sentences will end with a period.
Saving to Database:
* Each finalized sentence is saved to the database using an HTTP POST request to insert.php. Ensure your backend (insert.php) is properly configured to handle this request and insert data into your database.
