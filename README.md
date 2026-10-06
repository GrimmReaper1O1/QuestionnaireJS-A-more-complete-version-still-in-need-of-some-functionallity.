# QuestionnaireJS-A-more-complete-version-still-in-need-of-some-functionallity.
A close to finished E-learning solution under the MIT license
This is a framework made to be open source. Use it at your own risk. oAuthentication is disabled as it requires an ssl certificate and I'm poor, enough said. If enabling oAuthentication you will need to add the credentials part to every fetch statement.
The system still hasn't had all pages locked, I'm in the process of doing  it. As stated It's a framework to be completed or utilized.
I've had to utilize opensource AI to complete it quickly so there may be some problems with it that I'm still ironing out but for the most part it is fully functional.
Has: revolving multiple choice questions page and everything needed to configure it inclusive of json input to be used via AI for questions and subjects. Getting the ai to fulfill the request is a bit iffy though, better css, flash card system, administrative functionallity to create administrators with system to deny or permit access to pages that accomplish different things. results graph with the importing of chartjs 4 in the html file. insertion of video, appendix, and audio files and much more.
needs: flashcard results to be entered into the database as a written test system minor changes otherwise it's basically complete.

HTML needs to be placed in a folder in c:/inetpub/wwwroot for the thing to work also same for the server which needs to be placed in C:/server with all the folders in the server folder in the zip file. Database needs to be input into a mariadb server  the file is within the zip file. 
the sql file was made by an AI so it should include all the columns and tables but may not. You can find anything missing by the nodejs servers logs or window. Know that you need to run the server.js file in c:/server/server to run the server.
Otherwise I'll put up a video for the site in the future. The css is much better than it used to be.

