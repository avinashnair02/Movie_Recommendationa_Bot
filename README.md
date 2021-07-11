# 🤖 MovieRecommandationchatbot
Code repository for Moviebot – an NLP-powered movie recommendation chatbot, written in Python, HTML/CSS and JavaScript & hosted on Vercel + AWS Lambda.



![](https://github.com/avinashnair02/Movie_Recommendationa_Bot/blob/master/static/assets/Screenshot%202021-07-11%20at%2012.43.21%20PM.png)

![](https://github.com/avinashnair02/Movie_Recommendationa_Bot/blob/master/static/assets/Screenshot%202021-07-11%20at%2012.41.49%20PM.png)


Deployed Version of this Project: https://movie-recommendationa-bot.vercel.app

## 🖥 Running this locally 
To run this program locally, follow these steps:

1. Download the repo with `git clone https://github.com/avinashnair02/Movie_Recommendationa_Bot`
2. Create a virtual environment with `python3 -m venv venv`
3. Activate your virtual environment with `source venv/bin/activate`
4. Then, install all the required libraries with `pip install -r requirements.txt`
5. Next, export the Flask app route with `export FLASK_APP=index.py`
6. You will also need to export the Flask environment with `export FLASK_ENV=development`
7. Lastly, execute `flask run` and your program should be running at `http://127.0.0.1:5000/`

## ▲ Deploying on Vercel
To deploy this to vercel, all you gotta do is run `vercel --prod` in your terminal and follow through with the default setup criteria, as shown below:
```
? Set up and deploy “~/Desktop/username/moviebot”? [Y/n] y
? Which scope do you want to deploy to? vercel-username
? Link to existing project? [y/N] n
? What’s your project’s name? moviebot
? In which directory is your code located? ./
> Upload [====================] 98% 0.0sNo framework detected. Default Project Settings:
- Build Command: `npm run vercel-build` or `npm run build`
- Output Directory: `public` if it exists, or `.`
- Development Command: None
? Want to override the settings? [y/N] n
```
If you run into the error `zsh: command vercel not found`, you might need to run the following:

```
export PATH="/Users/macintosh/.npm-global/bin/:$PATH"
```


## 🐞 Question + Bug Fixes
Feel free to contact me at [avinashnair02@gmail.com](mailto:avinashnair02@gmail.com) for more information about this project.
