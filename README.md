<h1>Word on Cloud (WOC)</h1>
<h3>Overview</h3>
<p>People are starting to come out of their houses and gather again with decreasing number of COVID cases. Everyone is loving to interact with others, meet their loved ones, and have a leisure time with them. So, we decided to create a game. The list of things it can be useful for is endless. An individual can play it alone while in isolation or just for enjoyment. A professor can give test questions on this game and make the quiz entertaining. It can not only be played by small kids to whom this can help increase vocabulary, general knowledge, and any or every field they would like to explore, but professors at university can also provide students with the question of their related course. A host of the party can make the question of the quiz fun, and personal and leading to laughter. We are aiming at a high audience and above all to achieve the main motto of life which is FUN.</p>
<p>Our application will require registered users to log in to the game, also they need to be verified users. On login, the user will get two options. One option is to create a word and the other is to play.</p>
<p>When a user selects the option to play, they will be given a grid to enter a random word which can be guessed from the number of letters that word has. On guessing the word, the user will be provided with a hint on to how much extent the word is correct. If a letter of the word guessed is present in the actual word and is also present at the right place the letter will be highlighted in green, if the letter guessed is present in the actual word but is not at the right position then it will be highlighted in the gray and if the letter guessed is not present in the actual word, then it will be highlighted red. For example, the actual word is “cloud”, and someone guesses the word as “drone”. Here we can see that “o” is at the correct position so it will be highlighted green, “d” is present in the actual word but not at the correct position so it will be gray, “r”, “n” and “e” are not present in actual word so they will be highlighted in red color. The player will also be able to check the leaderboard which will show the number of times they have guessed the correct word, the average number of attempts, the average time it took for the correct attempt, and where they stand as compared to other people who played this word. In this format, the same word will be displayed to all people at a certain time to make the leaderboard unbiased. This word will change at specific intervals. Now let’s say the user forgot the password! Yes, they can update it. We will send a change password email to the user.</p>
<p>When the user selects the option to create a game. They can decide if they want to provide the hint in form of a question or just a word. Once they submit the hint and the answer, a link will be generated which can be shared with the group of people who wants to play. When this shared link is visited, the player does not require to register themselves. They can play directly, and this link will remain valid only for a specific time. In this format, we will not display the leaderboard.</p>
<p>In building this game we are using Amazon Web Services like Elastic Beanstalk, Lambda for computing, DynamoDB for storage, VPC for Network, and others. The game will be available as software to play and therefore, the delivery model is SaaS (Software as a Service).</p>
<h3>Build With</h3>
<ul>
<li>Backend: NodeJS</li>
<li>Frontend: React</li>
<li>Services Used: Elastic Beanstalk, Cognito, DynamoDB, S3, Event Bridge, Lambda, VPC and Cloud Formation</li>
<li>Hosted on: AWS Elastic Beanstalk</li>
</ul>
<h3>Application Screenshots</h3>
<h4>Cloud Architecture</h4>
<img width="1440" alt="login" src="https://user-images.githubusercontent.com/49091989/183277597-1e3d02c6-b80b-4b87-89ab-d0947dba6a60.jpg">
<h4>Login Page</h4>
<img width="1440" alt="login" src="https://user-images.githubusercontent.com/49091989/183275807-45532e69-528f-4830-9652-e3c8e8da0f26.png">
<h4>Signup Page</h4>
<img width="1440" alt="signup" src="https://user-images.githubusercontent.com/49091989/183275812-ac648352-552f-4316-9f34-730f25d0e69f.png">
<h4>Home Page</h4>
<img width="1440" alt="home" src="https://user-images.githubusercontent.com/49091989/183275803-1403d854-27ee-4502-89a4-c4dcee930c9f.png">
<h4>Playing a game</h4>
<img width="1440" alt="play" src="https://user-images.githubusercontent.com/49091989/183275809-999f2501-ec87-4adc-bde3-9b63c70e794f.png">
<h4>Game already played in that day</h4>
<img width="1440" alt="ifplayed" src="https://user-images.githubusercontent.com/49091989/183275804-c171b927-34aa-48ac-991c-cb49a3b02ada.png">
<h4>Leaderboard</h4>
<img width="1440" alt="leaderboard" src="https://user-images.githubusercontent.com/49091989/183275806-2773e6db-adb8-456f-9fc0-5adcf44604bf.png">
<h4>Validations</h4>
<img width="1440" alt="validations" src="https://user-images.githubusercontent.com/49091989/183275813-b81cbebf-e88b-47fc-b39a-0c52cd6a6709.png">
<h4>Create a custom game<h4>
<img width="1440" alt="creategame" src="https://user-images.githubusercontent.com/49091989/183275801-9c2758b8-958b-49f6-9579-852f30531312.png">
<h4>Access the link of created game</h4>
<img width="1440" alt="accesslink" src="https://user-images.githubusercontent.com/49091989/183275799-2e92ffc6-6867-4036-a7bb-969f8722292c.png">
<h4>Playing custom created game</h4>
<img width="1440" alt="playcustom" src="https://user-images.githubusercontent.com/49091989/183275810-9811e756-3041-4b96-9da1-7818c3f8a35b.png">
<h4>Forgot Password</h4>
<img width="1440" alt="forgot" src="https://user-images.githubusercontent.com/49091989/183275802-6b9e1b3c-c4d4-4f71-b8b5-d3a78ee5d871.png">
<h4>Email sent with verification code</h4>
<img width="375" alt="codesent" src="https://user-images.githubusercontent.com/49091989/183275800-7ddb00e0-3637-4814-a711-72f7e71e5cc7.png">
<h4>Resetting password</h4>
<img width="1440" alt="reset" src="https://user-images.githubusercontent.com/49091989/183275811-2d05f248-797e-48c9-99e7-2cd15fdf41a9.png">
<h4>Password resetted successfully</h4>
<img width="1440" alt="passwordreset" src="https://user-images.githubusercontent.com/49091989/183275808-0ce75f62-c6bd-4f9e-be33-5b08094ef2a7.png">
