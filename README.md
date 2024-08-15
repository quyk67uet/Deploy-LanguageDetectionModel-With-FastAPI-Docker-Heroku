# Deploy ML models with FastAPI, Docker, and Heroku
This is a language detector model which can predict 17 different languages.

Link for Datasets: https://www.kaggle.com/datasets/basilb2s/language-detection

### Sample
Here's a sample of what you can expect to see with this project:
<img width=600 src="https://imgur.com/mPqPKtc.jpeg" alt="">
<img width=600 src="https://imgur.com/KkybzwR.jpeg" alt="">

# 1. Create Docker container
- docker build -t app-name .

- docker run -p 80:80 app-name

# 2. Create Git repo
- git init
- git add .
- git commit -m "initial commit"
- git branch -M main

# 3. Create Heroku project
- heroku login
- heroku create your-app-name
- heroku git:remote your-app-name
- heroku stack:set container
- git push heroku main
