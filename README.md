# Aidan_Portfolio

## Project 1: FastAPI REST API
[Project Link](https://github.com/Turtle24/fastapi_project)

**Project At A Glance:**

A FastAPI project built using a weather api and a local instance of a MySQL database in order to explore the framework. I created a database connection, created post, get, put and delete endpoints. JWT, hashing and tokens were implemented for authentication to access the weather endpoints. The project was an exploration project as I wanted to learn more about FastAPI and implement aysncio. I implemented environment variables, requirements.txt and .gitignore in order to apply good practices.

![GitHub Logo](https://github.com/Turtle24/Aidan_Portfolio/blob/main/images/fastapi.jpg)

**Python Modules:**

1. FastAPI
2. dotenv
3. sqlalchemy
4. jose
5. pydantic
6. starlette


## Project 2: Picture Filter & Quote Overlay
[Project Link](https://github.com/Turtle24/photos_opencv)

**Project At A Glance:**

I wasn't sure what to get my mom for Christmas so I figured I'd create something with some real sentimental value for her. Essentially I pull stoic quotes from a website with beautifulsoup. I then randomize the image, quote and image effect to be used. The image effects are done with opencv and the text overlay is also performed with opencv. The image is then emailed to her via gmail. So once a week she will recieve an image via email. I used environmental variables and gitignore to avoid revealing passwords, used OOP techniques to make the project more Pythonic as this was my first project I completely redid it. I attempted to apply a lot of what I learnt and I intend to add more functionality as time goes on and I learn more. *The timer decorator was a learning excercise but I kept it just to see how fast each run is, might come in use down the road.

![GitHub Logo](/images/image14.jpg)

**Python Modules:**

1. beautifulsoup
2. json
3. opencv2
4. numpy
5. TextWrapper
6. email, smtplib, ssl

**Down The Road:**

- [ ] Use what I've learnt with selenium to scrape a better quotes website 
- [ ] Use Opencv to identify who is in the pictures
- [ ] Allow my mom to request new images via email
- [ ] Use FastAPI to run the above functionality
- [ ] Add more effects

## Project 3: Masters Group Project
[Project Link](https://github.com/Turtle24/Covid_Analytics_Project)

**Project At A Glance:**

My Masters group project, we chose covid as there's an abundance of data and research papers that we can investigate and possibly implement. Currently the project has a database setup. We've done descriptive statistics and I'm focusing on creating a semantic analysis of the vaccination tweets, next I'll do a sentiment analysis and gather more tweets of other topics to create a broader discussion. I've tested NLTK and Spacy, I intend to use both together as I've had more success with NLTK's tokenization. I'm going to test NLTK, Spacy and Sklearn's sentiment models to see what yields the best results and I'm going to use plotly to dashboard everything on a webapp. I want to create something unique that one else can replicate.

**Python Modules:**

1. sklearn
2. NLTK
3. Spacy
4. Numpy
5. Pandas
6. MySQL connector

**To-Do:**

- [ ] Improve data model
- [ ] Semantic Analysis
- [ ] Sentiment Analysis Model
- [ ] Webapp
- [ ] Visualisations


## Project 4: Custom Visualizations
[Project Link](https://github.com/Turtle24/CustomViz)

**Project At A Glance:**

I wanted to explore Bokeh, Flask and SQL to create custom visualisations. I used sklearn to run a basic regression on demo data however this project requires a bit of love and treatment as applied to the above. The data is in a local MySQL database and it's just stocks data, I intend to overhaul this over a weekend hover it isn't a priority at the moment thus I've put it on ice. I achieved my exploration goals and I am going to apply what I learnt to my Masters group project.

![GitHub Logo](/images/bokeh.PNG)

**Python Modules:**

1. sklearn
2. Flask
3. Bokeh
4. mysql
5. numpy
6. pandas

**To-Do:**

- [ ] Use another dataset
- [ ] Add quering on the webapp
- [ ] Test plotly
- [ ] Clean up visualisations
- [ ] Allow users to login and have custom views





