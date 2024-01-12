# StartUp
### notes for CS260 found in [notes.md](https://github.com/alexjames47/StartUp/blob/main/notes.md)
## Pitch
Do you wanna play bingo with your friends? Do you wanna create and compare your bingo cards? Do you think YOU have the most bingos? Then Create an account on BigNoBingo! You can do all that and more here at BIGNOBINGO, our powerful engine will help you design the perfect bingo card for you and your friends. No friends? No Problem! Join or open public rooms to play bingo with strangers and see who is the best BINGO-er. 
### Play Bingo with Friends
## Sketch
### Bingo Card Creation
![Bingo Creation](https://github.com/alexjames47/StartUp/blob/main/CreationPage.png)
### Bingo Card Playing
![Bingo Playing](https://github.com/alexjames47/StartUp/blob/main/PlayingPage.png)
### Login Page
![Login](https://github.com/alexjames47/StartUp/blob/main/BigNoLoginPage.png)
### Home Page
![Home](https://github.com/alexjames47/StartUp/blob/main/BigNoHomePage.png)

### Key features
Secure login over HTTPS - BigNo Accounts
Creating Bingo Cards
Choosing to Play or Create
Playing with a live chat room
Bingo card of other players can be viewed
Bingo cards created are stored and can be edited later


### Technologies
I am going to use the required technologies in the following ways.

**HTML** - Uses correct HTML structure for application. atleast Two HTML pages. One for login and one for creating a bingo card and one for playing Bingo. Hyperlinks to profiles

**CSS** - Application styling that looks good on different screen sizes, uses good whitespace, color choice and contrast.

**JavaScript** - Provides login, choice display, applying votes, display other users votes, backend endpoint calls.

**Service** - Backend service with endpoints for:
login
retrieving choices
submitting votes
retrieving vote status
DB/Login - Store users, choices, and votes in database. Register and login users. Credentials securely stored in database. Can't vote unless authenticated.

**WebSocket** - As each user votes, their votes are broadcast to all other users.

**React** - Application ported to use the React web framework.