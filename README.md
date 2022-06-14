This notebooks runs MaBoSS stuff

### Run in Binder : [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/sysbio-curie/MaBoSS_Course/main)

### Run locally with Docker and Docker-compose
```
git clone https://github.com/sysbio-curie/MaBoSS_Course
cd MaBoSS_Course
docker-compose up -d
```
	
And then open your browser to this url : http://localhost:8888/notebooks/

### Run locally with Docker
```
git clone https://github.com/sysbio-curie/MaBoSS_Course
cd MaBoSS_Course
docker build -t maboss_course .
docker run -p 8888:8888 -d maboss_course
```	

And then open your browser to this url : http://localhost:8888/notebooks/
