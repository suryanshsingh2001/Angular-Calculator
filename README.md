# Simple Calculator Using Angular

Lets see this as a test project deployed using Firebase

 [Website Link](https://angular-calculator-2cc80.web.app/) 


 ## Docker 🐳
The project is dockerized for easy deployment and scalability. To run the app using Docker, use the following commands:

1. Build the image 
```
docker build --pull --rm -f "Dockerfile" -t angularcalculator:latest "."
```
2. Run image
```
docker run --rm -d -p 80:80/tcp angularcalculator:latest 
```
