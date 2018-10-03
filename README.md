# Personal_Website
My own Personal Website

Hello,

This is supposed to be my personal website. I was able to do this thanks to the people at [FontAwesome](https://fontawesome.com) who made the icons i used, as well at the people at [Docker-Curriculum](https://docker-curriculum.com/) who helped me learn the basics of Docker, and who showed me the flask app that I modified to serve this website.

# Startup

You can put the website up and running using a docker container by simply using:

>docker run -p 8888:5000 tmdias/website

Alternatively, if you wish to make changes to the website, simply download this github project, make the required changes and build your own docker image, using:

>docker build -t "YourUsername"/website .

If you'd like to learn more about docker, i suggest starting with the tutorial at [Docker-Curriculum](https://docker-curriculum.com/).

# Suggestions

If you have any suggestions or bugs, feel free to let me know, or better yet, make a pull request!

Cheers!
