# Task Manager
#### CI walkthrough project


## Steps for deployment

##### 1. Create a New project on Heroku
##### 2. ***heroku login*** in Terminal
##### 3. ***heroku apps*** in terminal to check if connection has been established
##### 4. ***git init*** in Terminal
##### 5. Copy ***heroku git:remote -a task-menegeris*** from heroku to set it up in Heroku
##### 6. Create a requirements.txt ***pip3 freeze --local > requirements.txt***
##### 7. ***git add .*** in Terminal
##### 8. ***git commit -m""*** in Terminal
##### 9. Deploy on heroku ***git push heroku master***
##### 10. Create a ***echo web: python app.py > Procfile***
##### 11. add and commit