# BIOS0030
This test is designed to challenge the user's sense of number approximation.

The user is shown 3D figures with several colours and conformations.

The user must select an option between A, B, C and D to pick 2D images that do not match the given 3D figure.

Ensure (1) all qn(number)_slide photos and (2) spatialfunctions.py are downloaded before commencing the test

Enjoy!

Improvements in Version 2: overview

Code structure:

Separated specific operations into individual functions, called when the main function run_spatial_reasoning() is executed.
run_introduction() : Contains biodata collection and test briefing
run_spatial_reasoning() : calls run_introduction(), then runs spatial reasoning test and uploads data into Google Form.
generate_statistics(): retrieves historical test data to return the user's ranking in graph format.
Various functions defined for button execution
All code functions placed into spatialfunctions.py file. Main test code calls on functions within this file.

Biodata collection:

Formatted all text into HTML.
Updated text boxes:(instead of input(), Text() is used for improved UI)
Buttons to streamline responses (dropdown, radiobuttons)
Submit buttons present to confirm response
Added consent button for data collection
Added Textbox for 4-digit identifier
Added code processing responses to streamline formatting (e.g, for identifier tgFH is edited to become TGFH)

Test briefing:

Added sequence of text to brief user on how the test works, how long it is, how to record responses.
Added countdown to test start
