# JISAA How to run the app 
Please open the "upgraged chainsaw" codespaces 
(As i was trying different methods to solve Bad gateway error so I created and worked on new codespaces)
Just write docker compose up in the codespaces terminal 
and if you want to run this app on PyCharm or visual studio use python manage.py runserver 
and after that click on the server link
App might get an error on codespaces saying 502 Bad Gateway which is a Git problem(tried to solve it and solutions but found it Git have this problem)
Error link (https://aliab007-upgraded-chainsaw-x5wrwvgg444q2p9g9-8000.preview.app.github.dev/)
So if you also get the same error run the app on local host using pyhcarm/visual studio (python manage.py runserver) 
And afterthat come to codespaces and run the following command and run it (docker compose up) and after that a link wil lbe created DO NOT OPEN THAT LINK RATHER COPY THAT LINK AND PASTE IT IN THE NEW TAB AND IT SHOULD WORK FINE!! (that is the solution I came up with)
This is an Django App that integrates messaging with another messaging app (Slack).
It was made to solve the  problem of missing messages due to juggling different messaging platforms.
So any message sent on this app gets received on Slack. The Tech Stack are Django, Html, Slack  and all their requirements. 
You run the app by a click of the button, Sign up, you also add your Slack account to the App's Slack channel. When you are done, 
you can view Job Adverts and other information on the timeline, which you must have received also on Slack, then reply it.
