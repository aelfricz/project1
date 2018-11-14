Cousera Software Product Management Capstone:

(27) As a reader, I want the application to work in both portrait and landscape orientation, so that I can choose the way I view material
Acceptance criteria (1):
Given that I want the application to work in protrait mode
When the device is in protrait orientation
Then the content (including layout, text, pictures and navigation mentus) should be displayed in protrait optimized format.
Acceptance criteria (2):
Given that I want the application to work in landscape mode
When the device is in landscape orientation
Then the content (including layout, text, pictures and navigation mentus) should be displayed in landscape optimized format.
Acceptance criteria (3):
Given that I want the application to work in both landscape and protrait mode
When I rotate the device
Then the content should be displayed in the appropriate mode.

Acceptance test:
Prepare a set of sample pages (including main menu, browse, search, comphrension test, sample content) for testing.
Rotate the device to protrait orientation.
Go through all the pages and check if they are displayed correctly.
During each page rotatate to landscape and rotate back and check if content is displayed appropriately.


(28) As a reader, I want any pictures associated with the content to appear with the text, so that they can supplement the reading material
Acceptance criteria (1):
Given that I want to see the pictures that are associated with the content.
When I am reading through a story.
Then I want to see the pictures that all the pictures of this story (not pictures of another story).
And they should should be on the correct pages.
Acceptance criteria (2):
Given that I want to see the pictures that are associated with the content.
When I am reading through a story.
Then I want to see the pictures at on the correct pages
So thatr they reflext the content of the text on the page.
Acceptance criteria (3):
Given that I want to see the pictures to supplment the reading material.
When I am reading through a story.
Then I want to see the pictures at the correct size (not too big or too smnall)
And the text should be wrapped correctly to give the space of the picture.

Acceptance test:
Prepare 2 sample book with text and pictures for testing.
Read one of the books.
Check that the pictures and text are displayed appropriately according to acceptance criteria.
Read the other book.
Check for the same.


(29) As a reader, I want to be able to adjust font size, so that it is easier to read.
Acceptance criteria (1):
Given that I want to be able to adjust the font size.
When I am reading through a story,
Then I should be able to see a side menu with font-size options (Small, Medium, Large)
When I choose one of the font-size options
Then the font-size should adjust accordingly.
Acceptance criteria (2):
Given that I want to be able to adjust the font size to make it easier to read.
When I adjust the font-size
Then the display of the pictures, text, wrapping, and size menu should not be affected.

Acceptance test:
Prepare 2 sample book with text and pictures for testing.
Read one of the books.
Check that the pictures and text are displayed appropriately according to acceptance criteria.
Read the other book.
Check for the same.

(32) As a reader, I want to be able to connect with a remote user, so that I know if I have access to someone with whom I can read
Acceptance criteria (1):
Given that I want to be able to connect with a remote user
When I click on the 'connect' button on the main menu.
Then the system will check for other online users whom have also clicked on the 'connect' button.
And match me with one of them.
Acceptance criteria (2):
Given that I have clicked the 'connect' button and is waiting for a match.
Then I should see a hourglass sign at the side.
And in the meanwhile, I can continue to read by myself.
Acceptance criteria (3):
Given that I have clicked the 'connect' button and there is no suitable users online.
Then the hourglass sign should continue to stay.
And the system should continue to check if a suitable user comes online.
Acceptance criteria (4):
Given that I have clicked the 'connect' button and the matched is successful.
Then I should recieved a success notifcation informing me of the user whom I'm matched to.
And I can see a 'connected' status on the top of the window.
And I can see a status showing whether the other user is reading a book
And if the other user is reading a book, it should indicate the title and the page that the other user is reading.

Acceptance test:
Get 2 test users with 2 devices.
User 1 clicks on the 'Connect' button
Check for hour glass sign and if user is still possible to read.
User 2 clicks on the 'Connnect' button
Check on both screens for the success notifcations.
User 1 opens and reads a book, in meanwhile user 2 should check if the status of user 1 is reflected correctly.
Then, user 2 show opens and reads a book, in meanwhile user 1 should check if the status of user 2 is reflected correctly.

(33) As a reader, I want to read with a connected reader using audio, so that we can read together
Acceptance criteria (1):
Given that I want to read together with a connected reader.
When I am connected with another user.
Then device starts transmiting my voice to the other user in real time.
And starts transmiting the other user's voice to me in real time.
Acceptance criteria (2):
Given that I am connected with another user
When both of us are reading
Then we should be able to hear each other in real time loud and clear.

Acceptance test:
Get 2 users and connect them together
Let the users speak briefly to each other
Let each user open a sample book on their individual.
Let the 2 users read the content together.
Check on the loudness, clarity, and if there are any communication delays.
