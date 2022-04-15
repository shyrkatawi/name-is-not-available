<br>Loan App
<br>
<br>Purpose of the app:
<br>    Track loans between users
<br>
<br>App must have next abilities:
<br>    User registration (phone number, profile creation)
<br>User must have ability to search friends by phone, other properties and add to their contact list
<br>Loans list:
<br>    Who, how much, date of creation (days?), reason
<br>Ability to group loans by users
<br>Open all loans for selected user
<br>Ability to resolve loan by adding “positive” loan to user:
<br>    User1  -100$ 12 days ago Party
<br></br>User1  -120$ 6 days ago  “Will return by Friday”
<br></br>User1  +210$ 1 day ago  “Returned funds by card transfer”
<br>Show total stat by user after all calculations
<br>Add new loan:
<br>New loan form where user can select some event (loan name\reason), add list of users who participated (at least 2, who paid and who loan), ability to provide details (like for party: what was buyed, price for each item, who buyed, price). After the loan creation, the total price for each user should be calculated and added to separate loans list
<br>Ability to add not existing in the system profile
<br>“Ghost” profile will be provided without a real account.
<br>    If a user later registers the user with the same credential, the system should ask him to confirm data.
<br>    The app must have at least two languages support (Russian, English)
<br>
<br>
<br>
<br>
<br>Technical details:
<br>    Frontend: Angular
<br>Backend: NodeJS
<br>Database: MongoDB
<br>Host: Heroku (or any free), Mongo - official free sandbox
<br>
<br> токен https://livecodestream.dev/post/a-practical-guide-to-jwt-authentication-with-nodejs/
