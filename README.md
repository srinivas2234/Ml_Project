# Ml_Project
1. Github account
2. Heroku account
3. VS code
4. Git Ci
5. [Git commands] (https://git-scm.com/docs/gittutorial/)

Create virtual environment


``` 

conda create -p venv python ==3.7 -y 
```

To activate 


```

conda activate venv/
```
To install requirements


```

pip install -r requirements.txt 
```
to add changes to file


```

git add . 
git add <file names>
```
to check the changes


```
git status
```
to get all changes


```

git log
```
To get origin address https://github.com/srinivas2234/Ml_Project.git (fetch) origin  https://github.com/srinivas2234/Ml_Project.git (push)


```

git remote -v 
```
To push to github main branch


```

git push origin main 
``` 


HERUKU WEB SERVICE
1. HEROKU_EMAIL:<>
2. HEROKU_API_KEY:<>
3. HEROKU_APP_NAME: ml-regression-app
0r 


AWS SEB SERVICE
1. AWS_EMAIL:<>
2. AWS_API_KEY:<>
3. AWS_APP_NAME: ml-regression-app

Build docker Image
```
docker build -t <Imagename>:<tagname>

docker build -t ml-project:latest .
```
Note:Image name for docker must be lowercase

To list docker images
```
docker images
```
To run docker image
```
docker run -p 5000:5000 -e PORT=5000 d7eb3691c57e
```
To check whether it is working or not to go browser and enter localhost:5000